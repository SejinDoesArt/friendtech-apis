# Friendtech Available Old and New API Endpoints

### Users by Username
- **URL:** https://prod-api.kosetto.com/users-by-username/{username}
- **Method:** GET
- **Headers:** None
- **Example:** https://prod-api.kosetto.com/users-by-username/johndoe

### Top Users by Price
- **URL:** https://prod-api.kosetto.com/lists/top-by-price
- **Method:** GET
- **Headers:** None

### Top Clubs by Market Cap
- **URL:** https://prod-api.kosetto.com/lists/top-clubs-by-market-cap
- **Method:** GET
- **Headers:** None

### Top Buyers
- **URL:** https://prod-api.kosetto.com/lists/top-buyers
- **Method:** GET
- **Headers:** None

### Top Sellers
- **URL:** https://prod-api.kosetto.com/lists/top-sellers
- **Method:** GET
- **Headers:** None

### Trending Users
- **URL:** https://prod-api.kosetto.com/lists/trending
- **Method:** GET
- **Headers:** None

### Recent Messagers
- **URL:** https://prod-api.kosetto.com/lists/recent-messagers
- **Method:** GET
- **Headers:** None

### Token Holders for a User
- **URL:** https://prod-api.kosetto.com/users/{userId}/token/holders?requester={requesterAddress}&pageStart={pageStart}
- **Method:** GET
- **Headers:** 
  - Accept: application/json
  - Content-Type: application/json
- **Example:** https://prod-api.kosetto.com/users/123456/token/holders?requester=0x1234...&pageStart=0

### Token Holdings for a User
- **URL:** https://prod-api.kosetto.com/users/{userId}/token-holdings?requester={requesterAddress}&pageStart={pageStart}
- **Method:** GET
- **Headers:** 
  - Accept: application/json
  - Content-Type: application/json

### User Info
- **URL:** https://prod-api.kosetto.com/users/{userId}
- **Method:** GET
- **Headers:** None

### Wallet Info
- **URL:** https://prod-api.kosetto.com/wallet-info/{walletAddress}
- **Method:** GET
- **Headers:** None

### Search Users
- **URL:** https://prod-api.kosetto.com/v2/search/users?username={searchQuery}
- **Method:** GET
- **Headers:** 
  - Accept: application/json
  - Content-Type: application/json
  - Authorization: {token}
- **Note:** Requires Authorization header.

### Search Clubs
- **URL:** https://prod-api.kosetto.com/search-clubs?query={searchQuery}
- **Method:** GET
- **Headers:** 
  - Accept: application/json
  - Content-Type: application/json
  - Authorization: {token}
- **Note:** Requires Authorization header.

### User Points
- **URL:** https://prod-api.kosetto.com/points/{userId}
- **Method:** GET
- **Headers:** 
  - Accept: application/json
  - Content-Type: application/json
  - Authorization: {token}
- **Note:** Requires Authorization header.

### User Authentication
- **URL:** https://prod-api.kosetto.com/users/auth/{userId}
- **Method:** GET
- **Headers:** 
  - Accept: application/json
  - Content-Type: application/json
  - Authorization: {token}
- **Note:** Requires Authorization header.

### User by ID
- **URL:** https://prod-api.kosetto.com/users/by-id/{userId}
- **Method:** GET
- **Headers:** None

### Chat Room Notifications
- **URL:** https://prod-api.kosetto.com/notifications/chatRooms/{userId}
- **Method:** GET
- **Headers:** 
  - Accept: application/json
  - Content-Type: application/json
  - Authorization: {token}
- **Note:** Requires Authorization header.

### Get Twitter Auth Link
- **URL:** https://prod-api.kosetto.com/v2-user-twitter-auth-link
- **Method:** GET
- **Headers:** 
  - Accept: application/json
  - Content-Type: application/json
  - Authorization: {token}

### Twitter Check
- **URL:** https://prod-api.kosetto.com/users/{userId}/twitter-check
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with code and state

### Link Twitter
- **URL:** https://prod-api.kosetto.com/users/{userId}/link-twitter
- **Method:** POST
- **Headers:** Authorization required

### Unlink Twitter
- **URL:** https://prod-api.kosetto.com/users/{userId}/unlink-twitter
- **Method:** POST
- **Headers:** Authorization required

### Get Privy Login Recover Link
- **URL:** https://prod-api.kosetto.com/twitter/privy-login-recover-link
- **Method:** GET

### Privy Recovery
- **URL:** https://prod-api.kosetto.com/twitter/oauth/privy-recovery
- **Method:** POST
- **Body:** JSON with code and state

### Get Signature
- **URL:** https://prod-api.kosetto.com/signature
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with address

### Update Chat Room Notifications
- **URL:** https://prod-api.kosetto.com/notifications/chatRooms/{userId}
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with isEnabled

### Add to Watchlist
- **URL:** https://prod-api.kosetto.com/watchlist-users/{userId}
- **Method:** POST
- **Headers:** Authorization required

### Remove from Watchlist
- **URL:** https://prod-api.kosetto.com/watchlist-users/{userId}
- **Method:** DELETE
- **Headers:** Authorization required

### Get Watchlist Status
- **URL:** https://prod-api.kosetto.com/watchlist-users/{userId}
- **Method:** GET
- **Headers:** Authorization required

### Get Used Code
- **URL:** https://prod-api.kosetto.com/used-code
- **Method:** GET
- **Headers:** Authorization required

### Get Invite Codes
- **URL:** https://prod-api.kosetto.com/invite-codes
- **Method:** GET
- **Headers:** Authorization required

### Get Chat List
- **URL:** https://prod-api.kosetto.com/chat-list/{userId}?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Cached Chat List
- **URL:** https://prod-api.kosetto.com/chat-list/{userId}/cached
- **Method:** GET
- **Headers:** Authorization required

### Get Portfolio
- **URL:** https://prod-api.kosetto.com/portfolio/{userId}
- **Method:** GET
- **Headers:** Authorization required

### Get Messages
- **URL:** https://prod-api.kosetto.com/messages/{userId}?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Watchlist
- **URL:** https://prod-api.kosetto.com/watchlist?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Account Trade Activity
- **URL:** https://prod-api.kosetto.com/users/{userId}/account-trade-activity?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Friends Activity
- **URL:** https://prod-api.kosetto.com/friends-activity-v2/{userId}?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Cached Friends Activity
- **URL:** https://prod-api.kosetto.com/friends-activity-v2/{userId}/cached
- **Method:** GET
- **Headers:** Authorization required

### Get Global Activity
- **URL:** https://prod-api.kosetto.com/global-activity-v2?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Cached Friends Activity (Global)
- **URL:** https://prod-api.kosetto.com/friends-activity-v2/cached
- **Method:** GET
- **Headers:** Authorization required

### Get Recommendations
- **URL:** https://prod-api.kosetto.com/recommendations
- **Method:** GET
- **Headers:** Authorization required

### Get Upload URL
- **URL:** https://prod-api.kosetto.com/chat/{chatId}/upload-url
- **Method:** GET
- **Headers:** Authorization required

### Strip EXIF
- **URL:** https://prod-api.kosetto.com/strip-exif
- **Method:** POST
- **Body:** Image file

### Get Gating State
- **URL:** https://prod-api.kosetto.com/gating-state/{userId}
- **Method:** GET
- **Headers:** Authorization required

### Update Gating State
- **URL:** https://prod-api.kosetto.com/gating-state/{userId}
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with isAccepted

### Refresh Twitter Metadata
- **URL:** https://prod-api.kosetto.com/refresh-twitter-metadata/{userId}
- **Method:** POST
- **Headers:** Authorization required

### Update User Bio
- **URL:** https://prod-api.kosetto.com/users/{userId}/user-bio
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with userBio

### Send Message
- **URL:** https://prod-api.kosetto.com/messages/{userId}
- **Method:** POST
- **Headers:** Authorization required
- **Body:** Message content (JSON)

### Send Club Message
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/messages
- **Method:** POST
- **Headers:** Authorization required
- **Body:** Message content (JSON)

### Create User Post
- **URL:** https://prod-api.kosetto.com/user-posts
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with text

### Vote on User Post
- **URL:** https://prod-api.kosetto.com/user-posts/{postId}/votes
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with votesCast

### Get Vote Notifications
- **URL:** https://prod-api.kosetto.com/vote-notifications?pageKey={pageKey}
- **Method:** GET
- **Headers:** Authorization required

### Get Friends Posts
- **URL:** https://prod-api.kosetto.com/friends-posts?pageKey={pageKey}
- **Method:** GET
- **Headers:** Authorization required

### Get Global Posts
- **URL:** https://prod-api.kosetto.com/global-posts?pageKey={pageKey}
- **Method:** GET
- **Headers:** Authorization required

### Get User Post Votes
- **URL:** https://prod-api.kosetto.com/user-posts/{postId}/votes?pageKey={pageKey}
- **Method:** GET
- **Headers:** Authorization required

### Delete User Post
- **URL:** https://prod-api.kosetto.com/user-posts/{postId}
- **Method:** DELETE
- **Headers:** Authorization required

### Get Recent Posts
- **URL:** https://prod-api.kosetto.com/recent-posts?pageKey={pageKey}
- **Method:** GET
- **Headers:** Authorization required

### Mute User
- **URL:** https://prod-api.kosetto.com/muted-users/{userId}
- **Method:** POST
- **Headers:** Authorization required

### Get Unread Vote Notifications
- **URL:** https://prod-api.kosetto.com/unread-vote-notifications
- **Method:** GET
- **Headers:** Authorization required

### Update Last Read Message
- **URL:** https://prod-api.kosetto.com/messages/{userId}/lastRead
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with lastRead set to current timestamp

### Submit Turnstile Token
- **URL:** https://prod-api.kosetto.com/turnstile-token
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with token field

### Create User
- **URL:** https://prod-api.kosetto.com/users
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with fields:
  - name
  - username
  - turnstileToken
  - s3PfpKey
  - userBio
  - referredByUserId

### Get Profile Picture Upload URL
- **URL:** https://prod-api.kosetto.com/pfp-images-upload-url
- **Method:** GET
- **Headers:** Authorization required

### Get Club Profile Picture Upload URL
- **URL:** https://prod-api.kosetto.com/club-pfp-images-upload-url
- **Method:** GET
- **Headers:** Authorization required

### Update User
- **URL:** https://prod-api.kosetto.com/users
- **Method:** PATCH
- **Headers:** Authorization required
- **Body:** JSON with fields:
  - ftUsername
  - ftName
  - s3PfpKey

### Add Chat Message Reaction
- **URL:** https://prod-api.kosetto.com/chat-messages/{messageId}/reactions
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with field:
  - reactionType

### Remove Chat Message Reaction
- **URL:** https://prod-api.kosetto.com/chat-messages/{messageId}/reactions/{reactionType}
- **Method:** DELETE
- **Headers:** Authorization required

### Get Chat Message Reactions
- **URL:** https://prod-api.kosetto.com/chat-messages/{messageId}/reactions?reactionType={reactionType}&pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Club Message Reactions
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/messages/{messageId}/reactions?reactionType={reactionType}&pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Add Club Message Reaction
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/messages/{messageId}/reactions
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with field:
  - reactionType

### Remove Club Message Reaction
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/messages/{messageId}/reactions/{reactionType}
- **Method:** DELETE
- **Headers:** Authorization required

### Get Notifications
- **URL:** https://prod-api.kosetto.com/notifications?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Notification Badge
- **URL:** https://prod-api.kosetto.com/notifications/badge
- **Method:** GET
- **Headers:** Authorization required

### Update Last Read Notification
- **URL:** https://prod-api.kosetto.com/notifications/lastRead
- **Method:** POST
- **Headers:** Authorization required

### Get User's Following List
- **URL:** https://prod-api.kosetto.com/users/{userId}/following-list?requester={requesterId}&pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get User's Followers List
- **URL:** https://prod-api.kosetto.com/users/{userId}/followers-list?requester={requesterId}&pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Club Information
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}
- **Method:** GET
- **Headers:** Authorization required

### Get Club President
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/president
- **Method:** GET
- **Headers:** Authorization optional

### Get Club Price History
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/price-history
- **Method:** GET

### Get Club Members
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/members?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization optional

### Get Specific Club Member
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/members?user={username}
- **Method:** GET
- **Headers:** Authorization optional

### Vote for Club
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/votes
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with field:
  - userId

### Get Club Activity
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/activity?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get Club Messages
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/messages?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Create Club
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with fields:
  - description (optional)
  - ticker

### Update Club
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}
- **Method:** PATCH
- **Headers:** Authorization required
- **Body:** JSON with field:
  - ticker

### Get Club Upload URL
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/upload-url
- **Method:** GET
- **Headers:** Authorization required

### Add Club Moderator
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/mods
- **Method:** POST
- **Headers:** Authorization required
- **Body:** JSON with field:
  - userId

### Remove Club Moderator
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/mods
- **Method:** DELETE
- **Headers:** Authorization required
- **Body:** JSON with field:
  - userId

### Silence User in Club
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/silenced-users/{userId}
- **Method:** POST
- **Headers:** Authorization required

### Unsilence User in Club
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/silenced-users/{userId}
- **Method:** DELETE
- **Headers:** Authorization required

### Mute Club
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/mute
- **Method:** POST
- **Headers:** Authorization required

### Unmute Club
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/mute
- **Method:** DELETE
- **Headers:** Authorization required

### Get Club Notifications
- **URL:** https://prod-api.kosetto.com/clubs/{clubId}/notifications
- **Method:** GET
- **Headers:** Authorization required

### Get Airdrop Information
- **URL:** https://prod-api.kosetto.com/airdrop
- **Method:** GET
- **Headers:** Authorization required

### Get User's Club Holdings
- **URL:** https://prod-api.kosetto.com/users/{userId}/clubs-holding-list?pageStart={pageStart}
- **Method:** GET
- **Headers:** Authorization required

### Get ETH Price
- **URL:** https://prod-api.kosetto.com/eth-price
- **Method:** GET

### Get Pinned Chat Messages
- **URL:** https://prod-api.kosetto.com/chat/{chatId}/pinned
- **Method:** GET
- **Headers:** Authorization required

### Pin Chat Message
- **URL:** https://prod-api.kosetto.com/chat/{chatId}/pinned
- **Method:** POST
- **Headers:** Authorization required

### Unpin Chat Message
- **URL:** https://prod-api.kosetto.com/chat/{chatId}/pinned
- **Method:** DELETE
- **Headers:** Authorization required

---

For all these endpoints, replace {clubId}, {userId}, {chatId}, {pageStart}, and other placeholders with actual values. The Authorization header should contain the appropriate token for authenticated requests.

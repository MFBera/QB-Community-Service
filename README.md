# qb-community-service
Community service for QB

### Requirements
- QBCore
- qb-input
- qb-clothing

### Installation
- Integrate into qb radial-menu
- Set clothes from config
- Add this in your server.cfg : qb-community-service

### F3 Menu integrated
```
  {
            id    = 'communityservice',
            title = 'Kamu Cezası',
            icon = '#general',
            type = 'client',
            event = 'communityservice:client:AddCommunityService',
            shouldClose = true,
  },
```

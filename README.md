## Tech Stack:

- Next.js
- React
- Socket.io
- Prisma
- Tailwind
- MySQL


## Key Features:

- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- Delete & Edit messages in real time for all users
- Create Text, Audio and Video call Channels
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (@tanstack/query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Light / Dark mode
- Websocket fallback: Polling with alerts 
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk

## DAY-1

- create a fresh next.js app (npx create-next-app@latest)
- install shadcn ui (npx shadcn@latest init)
- create a sign-in or sign-out page
- create a sign-out button
- Dark Mode toggle button


## DAY-2

- Create a free TiDB clustor for SQL DB
- Create profile ,Channel ,Server ,Member Model 
- prevent Hot reload for making new PrismaClient() agian and again in db.ts file
- create a server join page if user is not join any page then redirect into this page

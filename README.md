# Create T3 App With VS Code Dev Container

This is a [T3 Stack](https://create.t3.gg/) project bootstrapped with `create-t3-app`. I added `.devcontainer` folder to make it easier to develop with VSCode and Docker.

This repo assume you use T3 Stack with TypeScript + tRPC + Prisma + NextAuth.js + Tailwind CSS with PostgreSQL.

## Set Up
1. [Install VS Code](https://code.visualstudio.com/)
2. [Install Docker](https://code.visualstudio.com/docs/devcontainers/tutorial#_install-docker)
3. [Install VS Code Dev Containers Extension](https://code.visualstudio.com/docs/devcontainers/tutorial#_install-the-extension)
4. Clone this repository
5. Copy `.env.example` to `.env` and fill in the necessary environment variables.
    - For now, you need to fill in `DISCORD_CLIENT_ID` and `DISCORD_CLIENT_SECRET` obtained from [Discord Developer Portal](https://discord.com/developers/applications).
6. [Open this repository in a VS Code Dev Container](https://code.visualstudio.com/docs/devcontainers/containers#_quick-start-open-an-existing-folder-in-a-container)
7. After the `postCreateCommand` - `npm install` is done, run `npm run db:push && npm run dev` to start the development server.
    
## What's next? How do I make an app with this?

We try to keep this project as simple as possible, so you can start with just the scaffolding we set up for you, and add additional things later when they become necessary.

If you are not familiar with the different technologies used in this project, please refer to the respective docs. If you still are in the wind, please join our [Discord](https://t3.gg/discord) and ask for help.

- [Next.js](https://nextjs.org)
- [NextAuth.js](https://next-auth.js.org)
- [Prisma](https://prisma.io)
- [Drizzle](https://orm.drizzle.team)
- [Tailwind CSS](https://tailwindcss.com)
- [tRPC](https://trpc.io)

## Learn More

To learn more about the [T3 Stack](https://create.t3.gg/), take a look at the following resources:

- [Documentation](https://create.t3.gg/)
- [Learn the T3 Stack](https://create.t3.gg/en/faq#what-learning-resources-are-currently-available) — Check out these awesome tutorials

You can check out the [create-t3-app GitHub repository](https://github.com/t3-oss/create-t3-app) — your feedback and contributions are welcome!

## How do I deploy this?

Follow our deployment guides for [Vercel](https://create.t3.gg/en/deployment/vercel), [Netlify](https://create.t3.gg/en/deployment/netlify) and [Docker](https://create.t3.gg/en/deployment/docker) for more information.

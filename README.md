# Stack Template

A minimalistic Next.js starter template with minimal setup and a modular design. Bring your own backend and database.

[Demo](https://stack-template.vercel.app/)

## Landing Page

![Landing Page](./assets/landing-page.png)

## Dashboard

![Dashboard](./assets/dashboard-overview.png)

## Getting Started

1. Clone the repository

    ```bash
    git clone git@github.com:stack-auth/stack-template.git
    ```

2. Install dependencies

    ```bash
    pnpm install
    ```

3. Register an account on [Stack Auth](https://stack-auth.com), copy the keys from the dashboard, and paste them into the `.env.local` file. Then, enable "client team creation" on the team settings tab.

    If you want to learn more about Stack Auth or self-host it, check out the [Docs](https://docs.stack-auth.com) and [GitHub](https://github.com/stack-auth/stack).

4. Start the development server and go to [http://localhost:3000](http://localhost:3000)

    ```bash
    pnpm dev 
    ```

## Features & Tech Stack

- Next.js 14 app router
- TypeScript
- Tailwind & Shadcn UI
- Stack Auth
- Multi-tenancy (teams/orgs)
- Dark mode

## Inspired by

- [Shadcn UI](https://github.com/shadcn-ui/ui)
- [Shadcn Taxonomy](https://github.com/shadcn-ui/taxonomy)

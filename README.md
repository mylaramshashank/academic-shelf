# Academic Shelf

Browse, order, and collect academic materials such as lab records and booklets.

## Project info

**URL**: https://lovable.dev/projects/bd85ef81-32d9-4128-8bdc-8fc3072119f0

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/bd85ef81-32d9-4128-8bdc-8fc3072119f0) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone https://github.com/mylaramshashank/academic-shelf.git

# Step 2: Navigate to the project directory.
cd academic-shelf

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

## Available scripts

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the Vite development server (configured for port 8080). |
| `npm run build` | Create the production build in `dist/`. |
| `npm run build:dev` | Create a build using Vite's development mode. |
| `npm run lint` | Run ESLint across the project. |
| `npm run preview` | Preview the production build locally. |

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## Current implementation notes

- The current account, product, cart, and order flows use browser `localStorage`. Their data is local to the browser and is not shared across devices.
- A Supabase client scaffold exists at `src/integrations/supabase/client.ts`, but the account and shopping flows currently use `localStorage`.
- The admin check is performed in client-side code and is not secure authorization. Do not rely on it to protect real administrative operations or sensitive data.
- The contact form currently displays a success message and clears its fields; it does not send the message to a backend.

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/bd85ef81-32d9-4128-8bdc-8fc3072119f0) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/features/custom-domain#custom-domain)

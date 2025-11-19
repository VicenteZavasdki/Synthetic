# Synthetic blog website

*Automatically synced with your [v0.app](https://v0.app) deployments*

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com/vicentezavasdki-1170s-projects/v0-synthetic-blog-website)
[![Built with v0](https://img.shields.io/badge/Built%20with-v0.app-black?style=for-the-badge)](https://v0.app/chat/uCqeXD4q4Bf)

## Overview

This repository will stay in sync with your deployed chats on [v0.app](https://v0.app).
Any changes you make to your deployed app will be automatically pushed to this repository from [v0.app](https://v0.app).

## Deployment

Your project is live at:

**[https://vercel.com/vicentezavasdki-1170s-projects/v0-synthetic-blog-website](https://vercel.com/vicentezavasdki-1170s-projects/v0-synthetic-blog-website)**

## Build your app

Continue building your app on:

**[https://v0.app/chat/uCqeXD4q4Bf](https://v0.app/chat/uCqeXD4q4Bf)**

## How It Works

1. Create and modify your project using [v0.app](https://v0.app)
2. Deploy your chats from the v0 interface
3. Changes are automatically pushed to this repository
4. Vercel deploys the latest version from this repository

## Cloudflare Deployment

This project uses `@cloudflare/next-on-pages` to deploy Next.js to Cloudflare Pages.

### Prerequisites

1.  **Cloudflare Account**: You need a Cloudflare account.
2.  **Wrangler CLI**: The project includes `wrangler` as a dev dependency, but you can also install it globally.

### Local Development

To preview the application as it would run on Cloudflare:

\`\`\`bash
npm run pages:preview
\`\`\`

### Deployment

To deploy to Cloudflare Pages:

1.  **Build the application:**
    \`\`\`bash
    npm run pages:build
    \`\`\`

2.  **Deploy:**
    \`\`\`bash
    npm run pages:deploy
    \`\`\`

### Configuration

-   **Compatibility Flags**: Ensure your Cloudflare Pages project has the `nodejs_compat` compatibility flag enabled.
-   **Environment Variables**: Set your environment variables in the Cloudflare Pages dashboard.

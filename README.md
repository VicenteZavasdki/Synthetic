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

This project is configured to be deployed as a Cloudflare Worker with Assets (or Cloudflare Pages).

### Automatic Deployment

The `build` script has been updated to automatically generate the Cloudflare Worker compatible output.

1. **Build**:
   \`\`\`bash
   npm run build
   \`\`\`
   This will run `next build` followed by `@cloudflare/next-on-pages` to generate the `.vercel/output/static` directory.

2. **Deploy**:
   \`\`\`bash
   npx wrangler deploy
   \`\`\`
   This will deploy the worker and assets defined in `wrangler.toml`.

### Local Development

To preview the application as it would run on Cloudflare:

\`\`\`bash
npm run pages:preview
\`\`\`

### Configuration

-   **Compatibility Flags**: The `wrangler.toml` file automatically sets the `nodejs_compat` flag.
-   **Environment Variables**: Set your environment variables in the Cloudflare dashboard or `.dev.vars` for local development.

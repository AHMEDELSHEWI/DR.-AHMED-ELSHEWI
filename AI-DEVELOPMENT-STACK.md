# Ahmed Elshewi AI Development Stack

This stack is the approved development toolkit for projects built with Claude, ChatGPT, Gemini, GitHub, and local coding agents.

## Web and commerce
- Shopify — e-commerce storefront and products
- Calendly — appointment scheduling
- Vercel — frontend and serverless deployment
- Netlify — static sites and web deployment
- Namecheap — domain registration and DNS
- GoDaddy — domain and hosting services

## AI and application development
- Higgsfield — AI media generation
- Flutter — cross-platform mobile apps
- React Native — cross-platform mobile apps

## Backend and cloud
- Supabase — database, authentication, storage, edge functions
- Firebase — authentication, database, storage, notifications, analytics

## Agent usage policy
- Use GitHub as the source of truth for code and configuration.
- Use Claude Code for repository implementation and local skills.
- Use ChatGPT for planning, review, documentation, and artifact generation.
- Use Gemini for additional code review and multimodal analysis when available.
- Never commit API keys, service-account files, passwords, or private tokens.
- Keep production credentials in each provider's encrypted secrets/environment-variable store.

## Setup order
1. GitHub repository and branch protection.
2. Supabase or Firebase backend.
3. Vercel or Netlify deployment.
4. Namecheap or GoDaddy domain and DNS.
5. Shopify and Calendly integrations when the project needs commerce or booking.
6. Flutter or React Native client.
7. Higgsfield media assets when required.

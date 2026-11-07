# CLOUDNEX Starter

This is a frontend-only prototype for the CLOUDNEX Minecraft Java + Bedrock hosting website.

## Open in Acode
1. Extract the ZIP.
2. Open the `cloudnex_starter` folder in Acode.
3. Open `index.html` and use Preview.

## Deploy to Netlify
1. Create a GitHub repository and upload `index.html`.
2. Import that repository into Netlify, or drag the folder into Netlify's manual deploy area.
3. Netlify will publish the static website.

## Important
This prototype does NOT create or run Minecraft servers. It stores demo server requests in the current browser's localStorage only. The status deliberately says "Not deployed".

For real hosting, next build:
- Supabase Auth + PostgreSQL with Row Level Security
- A trusted backend API
- A separate game-server machine/worker for Java and Bedrock
- Secure provisioning, resource limits, console streaming, file access and backups

Never put Supabase service-role keys, machine credentials, or server-control secrets in frontend JavaScript.

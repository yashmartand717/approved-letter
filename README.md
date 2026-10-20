# MDPL Project Approval Letters

A one-page static site. No build step.

## Deploy to Vercel (once)
Option A - website, no install:
1. Create a new GitHub repository and upload `index.html` and `vercel.json`.
2. On vercel.com: Add New > Project > Import that repository > Deploy.
   (Framework preset: Other. Leave build and output settings empty.)

Option B - command line:
    npx vercel deploy --prod
(run inside this folder, log in when asked)

## Update later
Replace index.html in the repository; Vercel redeploys automatically.

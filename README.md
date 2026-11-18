# De Vera Family Artist Portfolio System

A self-contained static HTML website. No Node.js, database, or build command is required.

## Deploy with GitHub and Vercel

1. Create a new GitHub repository, for example `de-vera-artist-portfolio`.
2. Upload `index.html` and `.gitignore` from this folder to the repository.
3. In Vercel, choose **Add New > Project > Import Git Repository**.
4. Select the GitHub repository.
5. Leave the default settings. If Vercel asks for values, use:
   - Framework Preset: `Other`
   - Build Command: leave blank
   - Output Directory: `.`
6. Click **Deploy**.

## Important limitation

This is a front-end prototype. Profiles, artwork uploads, approvals, and inquiries are stored in the visitor's browser using `localStorage`; they are not shared between visitors and are not stored in a server database. The demo usernames and passwords are visible in the HTML source, so do not use this authentication for a real production system.

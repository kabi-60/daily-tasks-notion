# Daily Tasks — Notion Embed

A small date-wise daily checklist with Previous / Next navigation.

## Deploy to Vercel
1. Create a new GitHub repository (for example `daily-tasks-notion`).
2. Upload `index.html` to the repository root.
3. Import that repository in Vercel and deploy. No build command or framework preset is required; it is a static site.
4. Copy the deployed `https://....vercel.app` URL.
5. In Notion, under the TODO LIST heading, type `/embed`, paste the Vercel URL, and choose **Embed**.
6. Resize the embed block to fit the width.

## Notes
- Tasks are saved in this browser's local storage. They remain when the same browser/device is used.
- This starter does not sync tasks across devices or between different users.
- Today's first page starts with four sample tasks; you can edit by removing and adding tasks.
- Previous/Next moves one calendar day at a time. Future dates are disabled.

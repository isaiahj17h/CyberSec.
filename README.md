# Isaiah Hernandez — Brightspeed Fiber Ohio card

Static mobile page in `public/`. Deploys to Vercel with no build step.

## Deploy (one time, ~2 minutes)
1. Go to https://vercel.com/new and sign in with GitHub.
2. Import this repo. Leave Framework Preset = "Other". Click **Deploy**.
3. Open the **production** link Vercel gives you (e.g. `https://<project>.vercel.app`).
   Use that one — the long "preview" links with random letters are login-protected by default and won't open on a stranger's phone.
4. Tap **Show QR Code** → anyone can scan it.

Every push to `main` redeploys automatically.

## Optional
- Profile photo: add `public/profile.jpg` (square works best).
- To pin the QR to one link (e.g. a custom domain), set `SITE_URL` near the bottom of `public/index.html`.

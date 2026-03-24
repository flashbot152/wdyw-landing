# wdyw.io Landing Site

Ready-to-deploy static site for wdyw.io.

## Files
- `index.html` — Main landing page
- `privacy.html` — Privacy policy (required for App Store)
- `.well-known/apple-app-site-association` — Universal links for iOS deep linking (needs Team ID filled in)

## Deploy Options

### Option A: Cloudflare Pages (recommended — free, fast)
1. Push this folder to a GitHub repo (e.g. `wdyw-landing`)
2. Go to cloudflare.com → Pages → Connect to Git → select the repo
3. Set `wdyw.io` as the custom domain in Cloudflare Pages settings
4. Done — deploys automatically on every push

### Option B: Netlify (also free)
1. Drag-and-drop this folder at app.netlify.com/drop
2. Set custom domain to wdyw.io

### Option C: GitHub Pages
1. Push to a repo named `wdyw-io`
2. Enable GitHub Pages from Settings → Pages
3. Point wdyw.io DNS to GitHub Pages IPs

## ⚠️ Before deploying AASA file
Replace `TEAMID` in `.well-known/apple-app-site-association` with your actual Apple Developer Team ID.
Find it at: https://developer.apple.com/account → Membership → Team ID

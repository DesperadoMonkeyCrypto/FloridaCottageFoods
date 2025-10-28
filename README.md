# Florida Cottage Foods
Static site deployed via GitHub Pages.

## Edit these before deploy
- `/index.html`: replace Stripe link, Notion directory URL, Google Forms (quotes + vendor).
- `/cities/*.html`: replace each PASTE_NOTION_VIEW_... with filtered Notion view.

## Build & Deploy
Settings → Pages → Deploy from a branch → Branch: `main` → `/ (root)`.
Custom domain: `floridacottagefoods.com`. Ensure the `CNAME` file exists at repo root.

## DNS (at your registrar)
A @ 185.199.108.153
A @ 185.199.109.153
A @ 185.199.110.153
A @ 185.199.111.153
CNAME www  ->  desperadomonkeycrypto.github.io

Enforce HTTPS in Pages settings.

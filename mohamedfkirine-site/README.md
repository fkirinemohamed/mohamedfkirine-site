# mohamedfkirine.com (Cloudflare Pages)

This is a simple static research website (HTML/CSS) ready to deploy on Cloudflare Pages.

## Folder structure
- `public/` is the build output directory (what Cloudflare Pages will publish).
- `public/assets/` contains the CV PDF.

## Deploy on Cloudflare Pages (Git integration)
1. Create a GitHub repository and upload the contents of this folder.
2. In Cloudflare Dashboard: Workers & Pages → Pages → Create a project → Connect GitHub repo.
3. Build settings:
   - Framework preset: None
   - Build command: (leave empty)
   - Build output directory: `public`
4. After it deploys, add your custom domain in: Pages project → Custom domains.

Tip: If you edit content, just push changes to GitHub and Cloudflare redeploys automatically.

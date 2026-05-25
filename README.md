# Bogen.ai Travel Agent — Lead Magnet Landing Page

A free AI tool landing page from Bogen.ai (AI consulting & coaching, founded by
Edmund Bogen). Visitors learn how to turn Claude into a personal travel agent.
Built as a lead magnet.

## What's here

- `index.html` — the complete landing page (single file, no dependencies)
- `social-card.svg` — branded social graphic source
- `social-card.png` — 1080x1080 export for Facebook / Instagram / LinkedIn

## How to publish on GitHub Pages

1. Create a new public repository (suggested name: `travel-agent`).
2. Upload all files to the repository.
3. Go to Settings -> Pages.
4. Under "Build and deployment," set Source to "Deploy from a branch."
5. Select branch `main` and folder `/ (root)`. Save.
6. Wait 1-2 minutes. The page goes live at:
   `https://<your-username>.github.io/<repo-name>/`

## Custom domain (optional, recommended)

To serve at `bogen.ai/travel`, set the custom domain in Settings -> Pages and
add the matching DNS records with your domain provider.

## Editing

Everything is in `index.html`. The prompt text lives inside the
`<pre id="prompt-text">` block. Brand colors are CSS variables at the top of
the `<style>` block (navy `#1a3e5c`, cyan `#00a8e1`).

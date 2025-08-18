# Dr Jeevan — Landing Page

Static landing page for Dr Jeevan (Neurologist, Ayurvedic Doctor & Osteopath).

## Local Development

Open `index.html` in your browser. No build step is required.

## Deployment (Render)

This repo includes `render.yaml` to deploy as a Static Site on Render.

Steps:
1. Create a new Static Site on Render and connect this GitHub repo.
2. Set Publish Directory to `.` (root).
3. Add your custom domain in Render and configure DNS.
4. Replace `DRJEEVAN_USERNAME` in `index.html` and `render.yaml` with the actual Instagram username.

## Instagram Gallery

Add public post permalinks into `instagram.json` to show embedded posts:

1. Open Instagram posts and copy their URLs (format: `https://www.instagram.com/p/<shortcode>/`).
2. Put them in `instagram.json` as a JSON array, for example:
   ```json
   [
     "https://www.instagram.com/p/SHORTCODE1/",
     "https://www.instagram.com/p/SHORTCODE2/",
     "https://www.instagram.com/p/SHORTCODE3/"
   ]
   ```
3. Commit and deploy. The page will render the official Instagram embeds.

## Contact Link

Instagram DMs are the primary contact. Buttons deep-link to the Instagram app on mobile, with a web fallback.

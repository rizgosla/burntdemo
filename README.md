# Burnt Crumbs — Homepage Mockup

Static HTML/CSS/JS homepage mockup for Burnt Crumbs (Irvine, CA).

## Deploy to Cloudflare Pages

1. Push this folder to a GitHub repo:
   ```
   git init
   git add .
   git commit -m "initial"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

2. Go to [Cloudflare Pages](https://pages.cloudflare.com/) → Create a project → Connect to Git

3. Select your repo. Build settings:
   - **Framework preset**: None
   - **Build command**: *(leave empty)*
   - **Output directory**: `/` (root)

4. Deploy — Cloudflare will serve `index.html` automatically.

## Files

```
index.html   — Main page
app.js       — Stop-motion + carousel interactions
media/       — All images (hero shots, product photos, slideshow frames)
```

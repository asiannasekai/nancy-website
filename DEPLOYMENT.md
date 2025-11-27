# Nancy Stone Website

This is the source code for Nancy Stone's professional website showcasing her book "Becoming a Midwife in a Free-standing Birth Centre."

## Deployment

This site is deployed on Netlify with automatic deployments from the main branch.

### Manual Deployment to Netlify

1. **Create a Netlify account** at https://netlify.com
2. **Connect your repository**:
   - Go to Netlify dashboard
   - Click "New site from Git"
   - Choose GitHub and select this repository
3. **Configure build settings**:
   - Build command: (leave empty or use `echo 'Static site'`)
   - Publish directory: `/` (root)
   - Branch to deploy: `main`
4. **Deploy**: Click "Deploy site"

### Alternative: Drag and Drop Deployment

1. Build the site locally (no build step needed for this static site)
2. Zip the following files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `Nancy Stone 7.jpg`
   - `nancy cover.webp`
   - `netlify.toml`
3. Drag and drop the zip file to Netlify dashboard

## Custom Domain

To use a custom domain:
1. Go to Site settings > Domain management
2. Add custom domain
3. Update DNS records as instructed by Netlify

## Environment

- Static HTML/CSS/JavaScript site
- No build process required
- Optimized for performance and SEO
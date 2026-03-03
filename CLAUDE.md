# bookpeg.com - Static Website

## About
Bookpeg is a website featuring children's stories and creative writing by Ursula West. It includes stories like "Flexi and the Glass Bead" and "Perception", plus a blog section.

## Hosting
- **Domain**: bookpeg.com (registered at GoDaddy)
- **DNS**: Cloudflare (free plan)
- **Hosting**: GitHub Pages (free)
- **Repo**: tommywun/bookpeg-website

## File Structure
- `index.html` - Homepage
- `*/index.html` - Content pages (flexi-and-the-glass-bead, perception, blog, etc.)
- `wp-content/uploads/` - Images
- `wp-content/themes/colormag/` - Theme CSS, JS, fonts
- `wp-content/plugins/` - Plugin CSS/JS
- `CNAME` - Domain mapping for GitHub Pages

## How to Edit
1. Change the HTML/CSS files you want to update
2. `git add .` then `git commit -m "description of change"`
3. `git push`
4. Site updates automatically in ~1 minute

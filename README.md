# 🚀 Hello Hugo – Custom Theme Template

This is a minimal Hugo static site with a custom theme built from scratch, deployed on [Railway](https://railway.app), using [Nixpacks](https://nixpacks.com) for lightweight, dependency-free setup.

## 🌐 Features

- ✅ Instant deployment with Hugo pre-installed (via Nixpacks)
- ✅ No Dockerfile required
- 🌍 Dynamic `baseURL` from Railway's public URL
- 🎨 Custom theme built from scratch - no external dependencies
- 🌟 Production build with Hugo and static serving via Caddy
- 🛠️ Full control over HTML structure and styling

---

## 🚀 Deploy

[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/deploy/hugo?referralCode=dPr4mc)
---
## 🎨 Customization

Since this site uses a custom theme built from scratch, you have complete control over:

- **HTML Structure**: Edit layouts in `layouts/` directory
- **Styling**: Add CSS directly to your layout files or create separate stylesheets
- **Content**: Add markdown files to `content/` directory
- **Configuration**: Modify `hugo.toml` for site-wide settings

## 👋 Notes

- Hugo is installed dynamically using Nixpacks — no manual install or image needed.
- Caddy serves your production-ready static files from the `public/` folder.
- No external theme dependencies - everything is built from scratch for maximum flexibility.
- Perfect starting point for creating your own custom Hugo theme.
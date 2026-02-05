# Prime Server

Your Raspberry Pi accessible from anywhere via GitHub Pages.

## Live Site
[https://cjayxyz.github.io/prime-server](https://cjayxyz.github.io/prime-server)

## Features
- ✅ Auto-fetches current tunnel URL from GitHub Gist
- ✅ Two viewing modes:
  - **Open in New Tab**: Direct access to Pi server
  - **Embed Here**: View content without leaving the page
- ✅ Beautiful gradient UI
- ✅ Loading animation
- ✅ Responsive design

## How It Works
1. Raspberry Pi runs Cloudflare tunnel (URL changes periodically)
2. Python script monitors tunnel and updates GitHub Gist every 5 minutes
3. This GitHub Pages site fetches the latest URL from Gist
4. You always get the current Pi URL, even as it changes

## Tech Stack
- Pure HTML/CSS/JavaScript
- GitHub Pages for hosting
- GitHub Gist for dynamic URL storage
- Cloudflare Tunnel for Pi access

## Setup
1. Create new GitHub repo: `prime-server`
2. Enable GitHub Pages (Settings → Pages → Deploy from main branch)
3. Push this code
4. Access at: `https://cjayxyz.github.io/prime-server`

## Local Development
Just open `index.html` in a browser - no build step needed!

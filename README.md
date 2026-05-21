# Qadbak marketing site

Static landing page for **[qadbak.com](https://qadbak.com)** — premium marketing for the [Qadbak](https://github.com/macdirtycow/qadbak) control panel.

## Deploy

Upload all files in this repository to the **document root** of `qadbak.com` (FTP, cPanel, rsync, etc.). `index.html` must be served at `/`.

- **Homepage:** `https://qadbak.com/`
- **Open panel** buttons link to `https://qadbak.com/login` (requires the [Qadbak Next.js app](https://github.com/macdirtycow/qadbak) on the same host or a reverse proxy).

## Contents

| Path | Description |
|------|-------------|
| `index.html` | Landing page |
| `assets/css/style.css` | Styles |
| `assets/js/main.js` | Mobile nav & FAQ |
| `assets/img/favicon.svg` | Favicon |

## Full panel deploy

For marketing **and** a working login on one domain, deploy the main [qadbak](https://github.com/macdirtycow/qadbak) repository with Nginx (`deploy/nginx-qadbak.conf`) instead of this static site only.

## License

Same as the main Qadbak project — see [Omiiba](https://omiiba.dev).

# ritstiftet.se

Single-page Hugo site, no theme. Content is in `layouts/index.html`, styles in `assets/css/main.css`.

    hugo server      # local preview
    hugo --minify    # build to public/

Cloudflare (Workers Builds): root directory `/`, build command `hugo --minify`, deploy command `npx wrangler deploy`. Set build variable `HUGO_VERSION` (e.g. 0.150.0). Assets are served from `public/` (see `wrangler.jsonc`).

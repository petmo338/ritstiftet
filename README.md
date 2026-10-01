# ritstiftet.se

Single-page Hugo site, no theme. Content is in `layouts/index.html`, styles in `assets/css/main.css`.

    hugo server      # local preview
    hugo --minify    # build to public/

Cloudflare (Workers/Pages) build settings: build command `hugo --minify`, output directory `public`.

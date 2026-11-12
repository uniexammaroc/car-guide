# Car Guide

Static site (no build step). Upload all files to the root of a GitHub repository named `car-guide`, then in **Settings > Pages** choose **Deploy from a branch > main > / (root)**.

## Replace before publishing
1. `YOUR-EMAIL@example.com` in `contact.html`, `about.html`, `privacy.html`
2. `YOUR-DOMAIN.com` in `sitemap.xml` and `robots.txt`
3. After AdSense approval: uncomment the script in `index.html` `<head>` and put your `ca-pub-...` ID; put the line from your account in `ads.txt`

## Custom domain on GitHub Pages
Add the domain in Settings > Pages, then at your registrar: apex A records 185.199.108.153, .109.153, .110.153, .111.153 and a `www` CNAME to `USERNAME.github.io`. Enable "Enforce HTTPS".

## Notes
- Photos load from Wikimedia (each has its own license; open a photo to see author and license).
- If you serve visitors in the EEA/UK, add a Google-certified consent banner before showing ads.

Cloudflare Pages redirects

Upload the complete extracted site, including the _redirects file in the build output root. Cloudflare Pages parses this file and applies HTTP 302 redirects for /visit/ routes. Opening index.html locally does not execute server redirects. robots.txt forbids crawling /visit/ routes; this does not guarantee removal of already indexed URLs.

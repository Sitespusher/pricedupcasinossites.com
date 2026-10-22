Affiliate redirects: HTTP 302
Cloudflare Pages: upload _redirects in the build output root.
Apache: upload .htaccess and enable mod_alias/mod_rewrite.
Nginx: include nginx-affiliates.conf inside the server block.
Static preview does not execute server redirects. The exported configuration is a snapshot.

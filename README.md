# en
RewriteEngine on
RewriteCond %{SERVER_PORT} 80 
RewriteRule ^(.*)$ https://541n/en/index.html$1 [R,L]

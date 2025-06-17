RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://toto-zhen.github.io/dragonfruit/index.html$1 [R,L]

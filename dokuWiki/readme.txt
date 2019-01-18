docker run -d -p 80:80 --name my_wiki \
-v /data/docker/dokuwiki/data:/dokuwiki/data \
-v /data/docker/dokuwiki/conf:/dokuwiki/conf \
-v /data/docker/dokuwiki/lib/plugins:/dokuwiki/lib/plugins \
-v /data/docker/dokuwiki/lib/tpl:/dokuwiki/lib/tpl \
-v /data/docker/dokuwiki/logs:/var/log \
  mprasil/dokuwiki

Next Go to
http://127.0.0.1/install.php

pour finaliser la config du wiki

# FFRL Website

Dies ist das repo der FFRL website

## Theme auschecken:
- git submodule init
- git submodule update

## Wordpress updaten:
Alles erst lokal pullen und lokal mergen (webserver sollte read-only bleiben)!

- git remote add wordpress git://github.com/WordPress/WordPress.git
- git pull wordpress $versionstag
- git push origin master

Auf webspace:
- git pull origin master

Ins WP Admin einloggen. Falls DB updates anstehen, wird das angezeigt.

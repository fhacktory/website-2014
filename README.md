website-2014
============

Le site utilise un framework de site statique appelé [Middleman](http://middlemanapp.com/)

Super simple à utiliser: tu mets tes sources dans le dossier source, avec l'extension correspondant au langage utilisé (genre .html.haml, .css.sass, etc...).
Tu fais:
- `bundle exec middleman` pour lancer un serveur de test,
- `bundle exec middleman build` pour compiler les assets dans /build, que tu upload sur le FTP

Le css se set dans style.css, et tu peux setter des règles différentes pour la responsiveness dans les autres fichiers (style-desktop, style-..., etc.)

Testes bien sur mobile, please

# Basic template

Dossier de structure-type pour un projet simple et basique.

Principe global : 
- un seul dossier de travail, pas de séparation (dossier "dev", dossier "www")
- fichier index.html issu de Schnaps.it
- styles issus de KNACSS (mise à jour automatique possible avec un `bower install`)

## Structure

```
index.php
styles.min.css 	(styles générés)
main.min.css 	(JS générés)
rss.xml
404.html
favicon.ico
bower.json		(config des dépendances)
.bowerrc		(config du chemin des dépendances)
.htaccess		(config apache)
.gitignore		(config de non-versionning)
	/includes
		footer.php
		header.php
		etc.php
	/img
		logo.png
		spacer.gif
	/videos
	/js
		global.js
	/css
		styles.less (styles de dev)
		/illust
		/fonts
		/css-includes
			/knacss
				/less
					/knacss.less
	/vendor
		/modernizr
		/bootstrap
		/jquery
```

##Install

TODO


##License

MIT



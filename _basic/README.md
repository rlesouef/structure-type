# Basic template

Dossier de structure-type pour un projet simple et basique.

Principe global : 
- un seul dossier de travail, pas de séparation (dossier "dev", dossier "www")
- fichier index.html issu de Schnaps.it
- styles issus de KNACSS (mise à jour automatique possible avec un `bower install`)

## Structure

```
index.html
favicon.ico
bower.json		(config des dépendances)
.bowerrc		(config du chemin des dépendances)
.htaccess		(config apache)
.gitignore		(config de non-versionning)
	/includes
		footer.php
		header.php
		etc.php
    /assets (contient /img, /videos, /css, /js, /vendor)
	   /img
		  logo.png
		  spacer.gif
	   /videos
	   /js
		  global.js (JS de dev)
            global.min.css (JS de prod)
	   /css
		  styles.less (styles de dev)
          styles.min.css  (styles de prod)
		  /img
		  /fonts
		  /css-includes
			 /knacss
				    /less
					   /knacss.less
	   /vendor
		  /modernizr
		  /bootstrap
		  /jquery
    /error
        404.html
```

##Install

TODO


##License

MIT



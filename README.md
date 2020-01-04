# Framework CSS

## Un framework CSS basé sur SASS par Nicolas Bertho

### Structure des dossiers et fichiers

* index.html
* **css** : dossier contenant les fichiers css
	* *app.css* : fichier de surcharge
	* **framework**
		* *framework.css* : framework
* **scss** : dossier contenant les fichiers de travail (SASS)
	* *app.scss* : fichier de surcharge
	* **framework**
		* *framework.scss* : fichier principal du framework (chargement des modules)
		* *_variables.scss* : variables du framework
		* **modules**
			* *_container.scss* : module des container
			* *_grilles.scss* : module des grilles
			* *_menus.scss* : module des menus
			* *_pagination.scss* : module des paginations
			* *_reset.scss* : module du reset
			* *_textes.scss* : module des textes
			* *_utilitaires.scss* : module des utilitaires

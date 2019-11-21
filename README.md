## Simple Html with includes

Ici utilité pour construire facilement des Newsletters / 
Avec Parcel.js & [posthtml](https://github.com/posthtml/posthtml-include). 

## objectif

Divisier le projet en plusieurs sous parties lisibles

## Lancement du projet

	git clone https://github.com/bernardchri/Simple-Html-Includes.git Simple-Html-Includes
	cd Simple-Html-Includes
	rm -rf .git
	npm install
	npm run dev

pour une version build

	npm run build

## Comment s'en servir 

Travaillez dans le dossier /src sur le fichier index.html et retrouvez l'export dans ./dist. Faire des includes grâche à 
	
	<module href="./src/header.html"></module>
	
**Attention** l'export se fait à partir de la racine, d'où le "./src"

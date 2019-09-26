## Simple Html with includes

Ici utilité pour construire facilement des Newsletters / 
Avec Parcel.js & posthtml. 

## objectif

Divisier le projet en plusieurs sous parties lisibles

## Lancement du projet

	git clone https://github.com/bernardchri/Simple-Html-Includes.git
	rm -rf .git
	npm install
	npm run start

pour une version build

	npm run build

## Comment s'en servir 

Travaillez dans le dossier /src sur le fichier index.html et retrouvez l'export dans ./dist. Faire des includes grâche à 
	
	<module href="./src/header.html"></module>
	
**Attention** l'export se fait à partir de la racine, d'où le "./src"

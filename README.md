## Simple newsletter constructor

Avec Parcel.js & posthtml. 

## objectif

Divisier le projet en plusieurs sous parties lisibles

## Lancement du projet

	npm i
	npm run start

pour une version build

	npm run build

## Comment s'en servir 

Travaillez dans le dossier /src sur le fichier index.html et retrouvez l'export dans ./dist. Faire des includes grâche à 
	
	<module href="./src/header.html"></module>
	
**Attention** l'export se fait à partir de la racine, d'où le "./src"
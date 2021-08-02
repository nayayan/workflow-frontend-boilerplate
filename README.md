# Guide pratique et outils pour développement UI/UX
## Installations requises
- __[VSCode](https://code.visualstudio.com/)__ - Édition du code source
  - __[Swissknife](https://marketplace.visualstudio.com/items?itemName=luisfontes19.vscode-swissknife)__ - Collection d'extensions pour VSCode
  - __[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)__ - Extension serveur HTTP local
- __[GIT](https://git-scm.com/downloads)__ - Contrôle des versions du code source
- __[NodeJS](https://nodejs.org/)__ - Gestion des librairies avec 'npm'
## Commencer un nouveau projet
### Création du code source et accès au dossier dans VSCode
    git clone https://github.com/noreading/bootstrap5-webpack-boilerplate.git nouveau-projet
    cd nouveau-projet
    code .
### Initialisation du GIT
    git init
### Modification du fichier package.json
```
{
    "name": "nouveau-projet",
    "description": "Description du nouveau-projet",
    "author": "Votre nom",
    "license": "MIT"
} 
```
### Installation des librairies et démarrage de l'environnement de développement
    npm install
    npm run dev
### Compilation d'une version prête au déploiement dans '/dist'
    npm run build
## Documentations externes
- __[bootstrap5-webpack-boilerplate](https://github.com/noreading/bootstrap5-webpack-boilerplate)__ - Fondation d'un projet HTML5 complet
- __[Bootstrap 5](https://getbootstrap.com/docs/5.0/customize/overview/)__ - Librairie UI/UX
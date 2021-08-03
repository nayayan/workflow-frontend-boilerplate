# Guide pratique et outils pour développement UI/UX
## Installations requises
- __[VSCode](https://code.visualstudio.com/)__ - Édition du code source.
  - __[Swissknife](https://marketplace.visualstudio.com/items?itemName=luisfontes19.vscode-swissknife)__ - Collection d'extensions pour VSCode.
  - __[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)__ - Extension serveur HTTP local.
- __[GIT](https://git-scm.com/downloads)__ - Contrôle des versions du code source.
- __[NodeJS](https://nodejs.org/)__ - Gestion des librairies 'npm'.
## Nouveau projet
### Création du code source
    git clone https://github.com/noreading/bootstrap5-webpack-boilerplate.git nouveau-projet
### Édition de la source dans VSCode
    code ./nouveau-projet
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
### Installation des librairies
    npm install
### Compilation d'une version de production dans '/dist'
    npm run build
## Développement du projet
### Démarrage de l'environnement de développement
    npm run dev
### Fichiers et dossiers importants au développement
| Chemin                     | Description |
| -------------------------: | ----------: |
| ./package.json             | Description et configuration du projet. |
| ./index.html               | Point d'entrée. |
| ./dist                     | Version compilée. |
| ./src                      | Code source. |
| ./src/js                   | Script JS principal. |
| ./src/scss                 | Feuilles de styles SASS. |
| ./src/scss/main.scss       | Importations des feuilles de styles. |
| ./src/scss/components      | Styles spécifiques aux composants. |
| ./src/scss/_fonts.scss     | Déclaration des variables typographique. |
| ./src/scss/_variables.scss | Déclaration des variables de style. |

## Documentations externes
- __[bootstrap5-webpack-boilerplate](https://github.com/noreading/bootstrap5-webpack-boilerplate)__ - Fondation d'un projet HTML5 complet.
- __[Bootstrap 5](https://getbootstrap.com/docs/5.0/customize/overview/)__ - Librairie UI/UX.
- __[SASS](https://sass-lang.com/documentation)__ - Librairie CSS.
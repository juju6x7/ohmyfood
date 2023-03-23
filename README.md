# Ohmyfood 🍴

Ohmyfood est un site 100% mobile qui répertorie les menus de restaurants gastronomiques.

# Objectifs 🎯

### Dynamiser les page web avec des animations CSS
- transitions
- @keyframes

### Utiliser SASS pour la partie CSS
- indentation du code
- organisation des fichiers via le pattern 7-1
- node.js

### Utiliser GitHub
- commits en lignes de commandes (git add *, status, commit -m "", git push, git branch...)
- Pages pour héberger le site

# Screenshots 📸
Responsive design (Desktop, Tablet, Mobile)

![screeshots](https://user-images.githubusercontent.com/98356784/226656328-5ed7c9af-45b0-44fc-9738-a1b030881ea6.jpg)

# Demo 👀

▶️ https://jujudev7.github.io/ohmyfood/

# Tuto Step by Step 👣
- Installer Node.js : https://nodejs.org/en/
- npm init
- npm install sass *(installation locale)* ou npm install -g sass *(installation globale)*
- Créer un script :
"scripts": {
"sass": "sass --watch ./sass/main.scss:./public/css/style.css"
},
- npm run sass

# Thusfood - Projet Angular

## Description


Thusfood est un projet Angular de landing page pour restaurant. Il simplifie le démarrage de projets de design en offrant un accès facile aux composants essentiels : `main`, `menu`, et `footer`.

Les sections incluent la page d'accueil, les détails des recettes, la liste des blogs, les articles de blog, et la page de contact.

Avec un design propre et moderne, Thusfood permet une navigation rapide et une utilisation conviviale pour une excellente expérience utilisateur.

## Prérequis
- [Node.js](https://nodejs.org/) (version 20.15.1)
- [npm](https://www.npmjs.com/) (version 10.8.1)
- [Angular CLI](https://angular.io/cli) (version 18.1.0)

## Installation

### 1. Cloner le dépôt
```bash
git clone https://github.com/ton-utilisateur/tpts.git
cd tpts
```

### 2. Installer les dépendances Node.js
```bash
npm install
```

### 3. Créer le projet Angular
```bash
ng new tpts --style=css --skip-tests=true
cd tpts
```

## Création des composants

### 1. Menu
```bash
ng generate component menu
```

### 2. Main
```bash
ng generate component main
```

### 3. Footer
```bash
ng generate component footer
```

## Structure du Projet

```
TPTS/
├── node_modules/
├── src/
│   ├── app/
│   │   ├── menu/
│   │   │   ├── menu.component.ts
│   │   │   ├── menu.component.html
│   │   │   ├── menu.component.css
│   │   ├── main/
│   │   │   ├── main.component.ts
│   │   │   ├── main.component.html
│   │   │   ├── main.component.css
│   │   ├── footer/
│   │   │   ├── footer.component.ts
│   │   │   ├── footer.component.html
│   │   │   ├── footer.component.css
│   │   ├── app.component.ts
│   │   ├── app.component.html
│   │   ├── app.component.css
│   ├── index.html
├── .gitignore
├── angular.json
├── package.json
├── package-lock.json
├── README.md
├── tsconfig.json
```

## Insertion des images

### Utilisation des liens d'images
Pour insérer une image à partir d'un lien, utilisez simplement l'URL de l'image.

```html
<!-- Exemple d'insertion d'image via un lien -->
<img src="https://example.com/path/to/image.jpg" alt="Description de l'image">
```

## Lancer le projet

Pour démarrer le serveur de développement :
```bash
ng serve
```
Accédez à l'application dans votre navigateur à l'adresse [http://localhost:4200](http://localhost:4200).

## Serveur de développement

Exécutez `ng serve` pour démarrer un serveur de développement. Naviguez vers `http://localhost:4200/`. L'application se rechargera automatiquement si vous modifiez l'un des fichiers source.

## Génération de code

Exécutez `ng generate component component-name` pour générer un nouveau composant. Vous pouvez également utiliser `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Compilation

Exécutez `ng build` pour compiler le projet. Les artefacts de construction seront stockés dans le répertoire `dist/`.

## Exécution des tests unitaires

Exécutez `ng test` pour exécuter les tests unitaires via [Karma](https://karma-runner.github.io).

## Exécution des tests de bout en bout

Exécutez `ng e2e` pour exécuter les tests de bout en bout via une plateforme de votre choix. Pour utiliser cette commande, vous devez d'abord ajouter un package qui implémente des capacités de test de bout en bout.

## Aide supplémentaire

Pour obtenir plus d'aide sur l'Angular CLI, utilisez `ng help` ou consultez la page [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli).


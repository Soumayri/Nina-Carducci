Voici un README amélioré intégrant les détails du rapport d'intervention et des rich snippets pour améliorer le référencement et l'accessibilité.

---

# Optimisation SEO et Accessibilité pour Nina Carducci

Bienvenue dans le dépôt GitHub pour le projet d'optimisation SEO et d'accessibilité du site web de Nina Carducci. Ce projet vise à améliorer les performances, le référencement local et l'accessibilité du site web d'une photographe talentueuse, Nina Carducci.

## Contenu du dépôt

- **.vscode/**: Configuration pour Visual Studio Code.
- **assets/**: Dossier contenant les ressources du site (images, styles, scripts).
- **index.html**: Page principale du site web.
- **sitemap.xml**: Plan du site pour aider les moteurs de recherche à indexer le contenu.
- **.gitignore**: Fichiers et dossiers à ignorer par Git.
- **README.md**: Document de présentation et d'instructions du projet.

## Objectifs du Projet

1. **Optimisation des Performances**: Améliorer le temps de chargement des pages en optimisant les images et le code.
2. **Référencement SEO**: Améliorer la visibilité du site sur les moteurs de recherche.
3. **Référencement Local**: Mettre en place le balisage Schema.org pour le référencement local.
4. **Accessibilité**: Assurer que le site est accessible à tous les utilisateurs, y compris ceux ayant des handicaps.
5. **Correction de Bugs**: Résoudre les problèmes de navigation et d'affichage des filtres dans la galerie d'images.

## Instructions pour Contribuer

1. **Cloner le dépôt**:
    ```bash
    git clone https://github.com/votre-utilisateur/nina-carducci-seo-optimisation.git
    cd nina-carducci-seo-optimisation
    ```

2. **Installer les dépendances** (si nécessaire):
    ```bash
    npm install
    ```

3. **Lancer le serveur local**:
    ```bash
    npm start
    ```

## Audit Initial

Avant les modifications, un audit complet a été réalisé pour identifier les points à améliorer. Les outils utilisés pour cet audit sont :

- **Lighthouse**: Pour les performances et les meilleures pratiques.
- **Wave**: Pour l'accessibilité.
- **Google Chrome DevTools**: Pour le débogage et l'analyse des performances.

## Modifications Apportées

### Optimisation des Images

Le projet comportait initialement 14 images pour un poids total de 23 MB. Les modifications suivantes ont été effectuées :

- Compression des images pour réduire leur taille.
- Conversion en format WebP pour une réduction de poids supplémentaire.
- Mise en place d’images responsive en fonction de la taille de l’écran.

Après ces modifications, le poids total des images est passé à 1,5 MB, soit un gain de 93,5 %.

### Suppression de CSS Inutile

- Analyse et suppression des lignes de code CSS inutilisées.
- Optimisation des fichiers `Bootstrap.css` et `style.css` en utilisant l’outil de couverture de code.

### Minification des Fichiers CSS et JS

- Minification des fichiers `style.css` et `maugallery.js` pour améliorer les performances.
- Compression des fichiers pour réduire la taille et éliminer les espaces inutiles, commentaires et caractères redondants.

### Accessibilité

- Ajout de textes alternatifs aux images.
- Ajout de labels aux formulaires.
- Ajout de descriptions et de la langue française aux pages.
- Amélioration du contraste des couleurs.
- Révision de la structure du site pour une meilleure accessibilité.

### Référencement Local

- Ajout de balises méta OpenGraph pour Facebook et des Twitter Cards.
- Ajout de balises d'en-tête appropriées.
- Amélioration de la structure du site pour une meilleure indexation par les moteurs de recherche.
- Ajout d’un script JSON-LD pour le référencement local.

### Correction de Bugs

- Correction de la navigation dans la modale de la galerie.
- Mise en évidence de la catégorie sélectionnée avec un fond doré.


Pour toute question ou support, vous pouvez me contacter par mail sur : Stud.soum@gmail.com ou via LinkedIn : www.linkedin.com/in/soumayri-el-hachimi-158909311


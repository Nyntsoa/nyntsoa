# Base Front-End Premium

## Lancer le site
Ouvrez `index.html` directement dans votre navigateur ou utilisez Live Server dans VS Code.

## COMMENT PERSONNALISER LE SITE

1. **Logo** : modifiez le bloc `.brand` dans les fichiers HTML et/ou remplacez le carré `brand-mark` par une image.
2. **Images** : remplacez les fichiers dans `images/hero`, `images/services`, `images/products`, `images/team`, `images/blog`, `images/portfolio` en gardant les mêmes noms, ou changez les chemins `src`.
3. **Textes** : recherchez les marqueurs entre crochets comme `[NOM DE L'ENTREPRISE]`, `[DESCRIPTION]`, `[PRIX]`.
4. **Couleurs** : modifiez les variables dans `css/style.css`, au début du bloc `:root`.
5. **Coordonnées** : éditez `contact.html` et le footer commun présent dans chaque page.
6. **Liens** : changez les attributs `href` dans les fichiers HTML. Tous les boutons principaux pointent déjà vers une page ou une action réelle.
7. **Ajouter une page** : dupliquez une page HTML, changez son `<title>`, son contenu `<main>` et ajoutez le lien dans la navbar.

## Notes
- Les formulaires sont validés côté Front-End. L'envoi réel nécessite un backend ou un service externe : `[BACKEND REQUIRED]`.
- L'authentification et le paiement réels nécessitent aussi un backend.
- Le projet utilise Google Fonts et Font Awesome via CDN.

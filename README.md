# ParoleLibre

ParoleLibre est une application web statique de communication assistée en français.

## Fonctionnement

- interface simple et tactile
- proposition de lettres par ordre de probabilité
- mots probables affichés séparément
- validation du mot en cours
- phrase construite progressivement
- compatible mobile et desktop

## Publication GitHub Pages

1. Créez un dépôt GitHub.
2. Uploadez le contenu du dossier `docs/` dans la branche principale ou dans votre branche de publication.
3. Dans les paramètres du dépôt, ouvrez la section `Pages`.
4. Choisissez `Deploy from a branch`.
5. Sélectionnez la branche principale et le dossier `/docs`.
6. Sauvegardez.

Le site est déjà prêt pour GitHub Pages avec la configuration suivante :
- `docs/index.html` comme page d’entrée
- `docs/.nojekyll` pour empêcher le traitement Jekyll

## Lancement local

Ouvrez simplement `docs/index.html` dans le navigateur, ou utilisez un petit serveur local si vous préférez.

Exemple :

```bash
python -m http.server 8000
```

Puis ouvrez `http://localhost:8000/docs/`.

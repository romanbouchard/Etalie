# Site officiel du gouvernement d'Étalie

Site statique en HTML/CSS pur, prêt à héberger sur GitHub Pages.

## Structure

```
index.html            → page d'accueil
ministeres.html        → liste des 14 ministères
municipalites.html     → répertoire des municipalités (à compléter)
portail-citoyen.html   → espace citoyen (à compléter)
actualites.html        → actualités officielles (à compléter)
contact.html           → coordonnées (à compléter)
css/styles.css         → feuille de style unique, partagée par toutes les pages
```

## Publier sur GitHub Pages

1. Crée un dépôt sur GitHub (ex. `etalie-gouvernement`).
2. Ajoute tous les fichiers de ce dossier à la racine du dépôt (garde le dossier `css/`).
3. Pousse le tout :
   ```bash
   git init
   git add .
   git commit -m "Site officiel du gouvernement d'Étalie"
   git branch -M main
   git remote add origin https://github.com/TON-NOM-UTILISATEUR/etalie-gouvernement.git
   git push -u origin main
   ```
4. Dans le dépôt GitHub : **Settings → Pages → Source**, choisis la branche `main` et le dossier `/ (root)`.
5. Ton site sera en ligne à `https://TON-NOM-UTILISATEUR.github.io/etalie-gouvernement/`.

## Pour continuer

Les pages `municipalites.html`, `portail-citoyen.html`, `actualites.html` et `contact.html`
contiennent chacune un bloc « en construction » — remplace-le par le vrai contenu au fur
et à mesure (une fiche par municipalité, une fiche par ministre, etc.), en réutilisant
le même en-tête/pied de page et les classes déjà définies dans `css/styles.css`
(`.carte-acces`, `.grille-acces`, `.entete-page`...) pour rester cohérent visuellement.

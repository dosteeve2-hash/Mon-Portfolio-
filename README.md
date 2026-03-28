# Steeve Do — Portfolio

Portfolio professionnel de Steeve Do, étudiant en Computer Engineering et passionné d'intelligence artificielle.

## Stack

- HTML / CSS / JS pur — aucune dépendance
- Déployé via Vercel (statique)
- Hébergé sur GitHub

## Déploiement

### Sur GitHub
1. Créer un nouveau repository (ex: `portfolio`)
2. Pousser les fichiers `index.html` et `vercel.json`

```bash
git init
git add .
git commit -m "Initial portfolio"
git remote add origin https://github.com/steevedoniba/portfolio.git
git push -u origin main
```

### Sur Vercel
1. Aller sur [vercel.com](https://vercel.com)
2. Cliquer **New Project**
3. Importer le repository GitHub
4. Vercel détecte automatiquement le projet statique
5. Cliquer **Deploy**

## Personnalisation

### Ajouter votre photo
Dans `index.html`, localiser la ligne :
```html
<img id="hero-photo" src="" alt="Steeve Do" style="display:none;" />
```
Remplacer `src=""` par le chemin de votre photo, ex: `src="photo.jpg"` (placer la photo dans le même dossier).

### Mettre à jour les liens
- Email : rechercher `steevedoniba@gmail.com`
- GitHub : rechercher `github.com/steevedoniba`
- LinkedIn : rechercher la section contact LinkedIn

## Licence
Portfolio personnel — tous droits réservés Steeve Do.

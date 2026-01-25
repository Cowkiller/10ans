# 🎉 Site "10 ans, ça se fête !" - Guide de déploiement

## Contenu du dossier

```
site-10ans/
├── index.html          # Le site complet
└── images/             # Toutes les photos
    ├── Mariage.jpeg
    ├── Julien_et_Alix_Vietnam.jpg
    ├── Gaspard_récente.jpeg
    ├── Le_petit_Monbouan.jpeg
    ├── Louison.jpeg
    ├── Sacha_et_Louison.jpeg
    └── Famille_maintenant.jpeg
```

## 🚀 Déploiement sur GitHub Pages (gratuit)

### Étape 1 : Créer un compte GitHub (si pas déjà fait)
1. Aller sur https://github.com
2. Cliquer sur "Sign up" et suivre les instructions

### Étape 2 : Créer un nouveau repository
1. Cliquer sur le "+" en haut à droite → "New repository"
2. Nom du repository : `10ans` (ou ce que tu veux)
3. Laisser "Public" coché
4. Cliquer sur "Create repository"

### Étape 3 : Uploader les fichiers
1. Sur la page du repository, cliquer sur "uploading an existing file"
2. Glisser-déposer TOUS les fichiers :
   - `index.html`
   - Le dossier `images` avec toutes les photos
3. En bas, cliquer sur "Commit changes"

### Étape 4 : Activer GitHub Pages
1. Aller dans "Settings" (onglet en haut)
2. Dans le menu de gauche, cliquer sur "Pages"
3. Sous "Source", sélectionner "Deploy from a branch"
4. Choisir la branche "main" et le dossier "/ (root)"
5. Cliquer sur "Save"

### Étape 5 : Récupérer l'URL
- Après quelques minutes, ton site sera accessible à :
  `https://TON-USERNAME.github.io/10ans/`

## 📝 Formulaire d'inscription

Le formulaire utilise **FormSubmit** (gratuit, sans inscription) :
- Les inscriptions seront envoyées à `alix.tran@gmail.com` ET `julien.tuvache@gmail.com`
- **Important** : La première soumission déclenchera un email de confirmation FormSubmit
- Clique sur le lien dans cet email pour activer le formulaire

## ✏️ Personnalisations possibles

### Modifier le texte d'introduction
Cherche `<div class="intro-text">` dans le fichier HTML et modifie le texte.

### Modifier les coordonnées GPS
Cherche `47.9234` et `-1.2847` et remplace par les vraies coordonnées.
Pour les trouver : cherche ton adresse sur Google Maps, clic droit → "Coordonnées".

### Modifier la carte Google Maps
1. Va sur Google Maps
2. Cherche "Le Petit Monbouan, 35680 Moulins"
3. Clique sur "Partager" → "Intégrer une carte"
4. Copie le code `<iframe>` et remplace celui dans le fichier HTML

### Ajouter des hébergements
Cherche la section `<div class="hebergements-list">` et ajoute des `<div class="hebergement-item">`.

## 🎨 Couleurs du site (style guinguette)

- Rouge brique : #B85042
- Crème : #FDF6E3
- Vert sauge : #6B8E6B
- Ocre : #D4A574

Tu peux les modifier dans la section `:root` au début du CSS.

## 📱 Le site est responsive !

Il s'adapte automatiquement aux téléphones, tablettes et ordinateurs.

---

Bon anniversaire de mariage ! 🥂

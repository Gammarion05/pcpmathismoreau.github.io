# Portfolio BTS SISR - Guide de mise en ligne sur GitHub Pages

## 📁 Fichiers du site
Votre site contient 3 fichiers :
- `index.html` - La page principale avec tout le contenu
- `styles.css` - Les styles (couleurs bleu/blanc/noir)
- `script.js` - L'interactivité (menu, navigation)

## 🚀 Comment mettre en ligne sur GitHub Pages

### Étape 1 : Créer un compte GitHub
1. Va sur https://github.com
2. Clique sur "Sign up" (gratuit)
3. Crée ton compte avec ton email

### Étape 2 : Créer un nouveau repository
1. Une fois connecté, clique sur le "+" en haut à droite
2. Choisis "New repository"
3. Nomme-le : `ton-nom.github.io` (remplace "ton-nom" par ton prénom ou pseudo)
   - Exemple : `pierre-martin.github.io`
4. Laisse en "Public"
5. Clique sur "Create repository"

### Étape 3 : Upload tes fichiers
1. Sur la page de ton repository, clique sur "uploading an existing file"
2. Glisse-dépose les 3 fichiers (index.html, styles.css, script.js)
3. En bas de page, clique sur "Commit changes"

### Étape 4 : Activer GitHub Pages
1. Dans ton repository, clique sur "Settings" (en haut)
2. Dans le menu de gauche, clique sur "Pages"
3. Sous "Source", sélectionne "main" (ou "master")
4. Clique sur "Save"
5. Attends 1-2 minutes

### Étape 5 : Accéder à ton site
Ton site sera accessible à l'adresse :
```
https://ton-nom.github.io
```

## ✏️ Comment modifier ton contenu

### Modifier le contenu
1. Télécharge le fichier `index.html`
2. Ouvre-le avec un éditeur de texte (Notepad++, VSCode, ou même Bloc-notes)
3. Cherche les sections entre crochets `[...]` et remplace-les par ton contenu :
   - `[Nom de l'entreprise]` → Nom de ta boîte de stage
   - `[Dates du stage]` → Ex: "Janvier - Février 2024"
   - `[Titre de la mission]` → Ex: "Installation d'un serveur Windows"
   - etc.
4. Sauvegarde le fichier
5. Retourne sur GitHub et remplace l'ancien fichier par le nouveau

### Conseils de modification
- **Les missions** : Décris ce que tu as fait concrètement
- **Les compétences** : Liste les technologies (Windows Server, VMware, Cisco, etc.)
- **Les tags B1.1, B2.2, etc.** : Réfère-toi au référentiel SISR pour mettre les bons numéros

## 🎨 Personnalisation des couleurs (optionnel)

Si tu veux changer les couleurs, ouvre `styles.css` et modifie les lignes 2-5 :
```css
--primary-blue: #0A66C2;     /* Couleur principale bleue */
--dark-blue: #003d82;        /* Bleu foncé */
--light-blue: #3b8dd4;       /* Bleu clair */
```

Tu peux utiliser un color picker en ligne pour choisir tes couleurs.

## 📱 Test en local

Avant de mettre en ligne, tu peux tester :
1. Ouvre `index.html` avec ton navigateur (double-clic sur le fichier)
2. Vérifie que tout s'affiche bien
3. Teste les menus déroulants

## ❓ Problèmes courants

**Le site ne s'affiche pas ?**
- Attends 5-10 minutes après l'activation de GitHub Pages
- Vérifie que les 3 fichiers sont bien uploadés
- Vérifie que GitHub Pages est activé dans Settings > Pages

**Les styles ne s'appliquent pas ?**
- Les 3 fichiers doivent être dans le même dossier (pas de sous-dossiers)
- Les noms de fichiers doivent être exactement : `index.html`, `styles.css`, `script.js`

**Le menu ne fonctionne pas sur mobile ?**
- C'est normal en local, teste une fois en ligne sur GitHub Pages

## 🎓 Pour ton oral

Points à mentionner :
- Tu as créé un site responsive (qui s'adapte au mobile)
- Tu utilises GitHub Pages (hébergement gratuit)
- Le site présente clairement tes compétences SISR
- Navigation simple et professionnelle

Bon courage pour ton BTS ! 💪

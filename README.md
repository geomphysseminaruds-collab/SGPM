# Séminaire de Géométrie - Site Web

Site web du séminaire de géométrie du Département de mathématiques de l'Université de Sherbrooke.

## 📁 Structure du projet

```
geometry-seminar/
│
├── index.html          # Page d'accueil
├── upcoming.html       # Séminaires à venir
├── past.html          # Séminaires passés
├── members.html       # Membres du groupe de recherche
├── events.html        # Événements spéciaux
├── gallery.html       # Galerie de photos
│
├── styles.css         # Feuille de style principale
├── script.js          # JavaScript (gestion langue, navigation)
│
└── README.md          # Ce fichier
```

## 🎨 Thème et couleurs

Le site utilise le thème de l'Université de Sherbrooke avec :
- Couleur principale : `#00703c` (vert UdeS)
- Typographie : System fonts (Apple, Segoe UI)
- Design responsive et moderne

## 🌐 Fonctionnalités

### Bilingue (Français/Anglais)
- Changement de langue dynamique
- Préférence sauvegardée dans localStorage
- Contenu disponible dans les deux langues

### Navigation
- Menu sticky en haut de page
- Indication de la page active
- Liens internes et externes

### Pages

1. **index.html** - Page d'accueil
   - Présentation du séminaire
   - Informations générales
   - Prochain séminaire

2. **upcoming.html** - Séminaires à venir
   - Liste des présentations futures
   - Détails complets (date, lieu, conférencier, résumé)

3. **past.html** - Séminaires passés
   - Archives des séminaires précédents
   - Résumés complets

4. **members.html** - Membres
   - Organisateurs
   - Professeurs
   - Postdoctorants
   - Doctorants

5. **events.html** - Événements
   - Événements spéciaux à venir
   - Archives d'événements passés

6. **gallery.html** - Galerie
   - Photos des séminaires
   - Photos d'événements

## 🚀 Installation et déploiement

### Installation locale

1. Clonez le dépôt ou téléchargez les fichiers
2. Ouvrez `index.html` dans un navigateur

Aucune compilation n'est nécessaire - c'est du HTML/CSS/JS pur.

### Déploiement sur GitHub Pages

1. Créez un dépôt GitHub
2. Poussez tous les fichiers
3. Allez dans Settings > Pages
4. Sélectionnez la branche `main` comme source
5. Le site sera disponible à : `https://username.github.io/repository-name/`

### Structure recommandée pour GitHub Pages

```
docs/
├── index.html
├── upcoming.html
├── past.html
├── members.html
├── events.html
├── gallery.html
├── styles.css
├── script.js
└── images/          # Ajoutez vos images ici
    ├── seminars/
    ├── events/
    └── gallery/
```

## 📝 Personnalisation

### Modifier les couleurs

Dans `styles.css`, changez :
```css
/* Couleur principale UdeS */
#00703c → votre couleur
```

### Ajouter un séminaire

Dans `upcoming.html` ou `past.html`, ajoutez :

```html
<div class="seminar-item">
    <h3 class="seminar-title">Titre du séminaire</h3>
    <div class="seminar-meta">
        <span><strong>Date :</strong> Votre date</span>
        <span><strong>Lieu :</strong> Votre lieu</span>
    </div>
    <div class="seminar-speaker">
        <a href="#">Nom du conférencier</a>, Institution
    </div>
    <div class="seminar-abstract">
        <strong>Résumé :</strong> Votre résumé...
    </div>
</div>
```

### Ajouter un membre

Dans `members.html`, ajoutez :

```html
<div class="member-card">
    <div class="member-name">Nom</div>
    <div class="member-title">Titre</div>
    <div class="member-research">Spécialités de recherche</div>
</div>
```

### Ajouter des photos

1. Créez un dossier `images/`
2. Ajoutez vos photos
3. Dans `gallery.html`, remplacez :

```html
<div class="gallery-item">
    <img src="images/votre-photo.jpg" alt="Description">
</div>
```

## 🔧 Maintenance

### Mettre à jour le contenu

- **Séminaires** : Déplacez les séminaires de `upcoming.html` vers `past.html` après qu'ils ont eu lieu
- **Événements** : Mettez à jour `events.html` avec les nouveaux événements
- **Membres** : Ajoutez/retirez des membres dans `members.html`

### Tests

Testez le site dans différents navigateurs :
- Chrome/Edge
- Firefox
- Safari
- Sur mobile

## 📱 Responsive Design

Le site est entièrement responsive et s'adapte aux :
- 📱 Téléphones (< 768px)
- 💻 Tablettes (768px - 1024px)
- 🖥️ Ordinateurs (> 1024px)

## 🤝 Contact

Pour toute question sur le site :
- Email : geometrie.seminaire@usherbrooke.ca

## 📄 Licence

© 2025 Université de Sherbrooke - Département de mathématiques

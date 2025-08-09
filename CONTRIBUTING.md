# Guide de Contribution - A.P.KA Website

Merci de votre intérêt à contribuer au site web de l'Alliance Politique des Kasavubistes ! 

## 🤝 Comment Contribuer

### 1. Signaler un Problème (Issue)

Si vous trouvez un bug ou avez une suggestion :

1. Vérifiez d'abord que le problème n'a pas déjà été signalé
2. Créez un [nouveau issue](../../issues/new)
3. Décrivez clairement le problème ou la suggestion
4. Ajoutez des captures d'écran si nécessaire

### 2. Proposer des Modifications

#### Setup Initial

```bash
# 1. Fork le repository sur GitHub
# 2. Clone votre fork
git clone https://github.com/VOTRE-USERNAME/apka-website.git
cd apka-website

# 3. Ajoutez le repository original comme remote
git remote add upstream https://github.com/ORIGINAL-USERNAME/apka-website.git
```

#### Workflow de Développement

```bash
# 1. Créez une nouvelle branche
git checkout -b feature/nom-de-votre-fonctionnalite

# 2. Faites vos modifications
# Éditez les fichiers nécessaires

# 3. Testez vos modifications localement
# Ouvrez index.html dans votre navigateur

# 4. Commit vos changements
git add .
git commit -m "Description claire de vos modifications"

# 5. Push vers votre fork
git push origin feature/nom-de-votre-fonctionnalite

# 6. Créez une Pull Request sur GitHub
```

## 📋 Types de Contributions

### 🐛 Corrections de Bugs
- Fautes de frappe
- Liens brisés
- Problèmes d'affichage
- Erreurs JavaScript

### ✨ Nouvelles Fonctionnalités
- Améliorations de l'interface
- Nouvelles sections
- Optimisations de performance
- Accessibilité

### 📝 Contenu
- Mise à jour des textes
- Nouvelles images
- Articles de blog
- Traductions

### 🎨 Design
- Améliorations CSS
- Responsive design
- Animations
- UX/UI

## 📝 Standards de Code

### HTML
```html
<!-- Utilisez une indentation de 4 espaces -->
<!-- Utilisez des balises sémantiques -->
<section class="section" id="nom-section">
    <div class="container">
        <h2 class="section-title">Titre</h2>
        <p class="section-subtitle">Sous-titre</p>
    </div>
</section>
```

### CSS
```css
/* Organisez les styles par sections */
/* Utilisez les variables CSS existantes */
.nouvelle-classe {
    color: var(--blue);
    background: var(--light);
    transition: var(--transition);
}

/* Commentez les sections importantes */
/* Section des styles pour le header */
```

### JavaScript
```javascript
// Utilisez des noms de variables clairs
// Ajoutez des commentaires pour les fonctions complexes
function nouvelleFeature() {
    // Description de ce que fait la fonction
    // ...
}
```

## 🎯 Checklist avant Pull Request

- [ ] ✅ Le code fonctionne correctement
- [ ] 📱 Le site est responsive (mobile, tablette, desktop)
- [ ] 🌐 Testé sur différents navigateurs
- [ ] 📝 Le contenu est en français correct
- [ ] 🎨 Le design respecte l'identité visuelle A.P.KA
- [ ] ♿ L'accessibilité est préservée
- [ ] 📄 La documentation est mise à jour si nécessaire

## 🚫 Ce qu'il faut éviter

- ❌ Modifications majeures sans discussion préalable
- ❌ Ajout de dépendances lourdes sans justification
- ❌ Changements qui cassent le design existant
- ❌ Contenu non lié à l'A.P.KA
- ❌ Code non commenté ou mal structuré

## 📞 Besoin d'Aide ?

- 💬 Ouvrez un [issue](../../issues) pour poser des questions
- 📧 Contactez-nous à ngueyipaul@gmail.com
- 📱 WhatsApp : [+243830497332](https://wa.me/243830497332)

## 🏛️ Code de Conduite

En participant à ce projet, vous acceptez de respecter nos valeurs :

- **Respect** - Traitez tous les contributeurs avec respect
- **Intégrité** - Soyez honnête dans vos contributions
- **Collaboration** - Travaillez ensemble vers un but commun
- **Excellence** - Visez la qualité dans tout ce que vous faites

## 📜 Licence

En contribuant, vous acceptez que vos contributions soient sous la même licence que le projet.

---

**Merci de contribuer à perpétuer l'héritage de Joseph Kasavubu ! 🇨🇩**

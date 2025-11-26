# 🎮 Application de Gestion des Propositions de Jeux

Une application web complète pour gérer les propositions de sessions de jeu entre un créateur de contenu et sa communauté.

## ✨ Fonctionnalités

### Pour les Joueurs (Page Publique)
- 📝 Formulaire simple pour proposer une session de jeu
- 🎯 Renseigner : pseudo, email, jeu, date, horaire
- 📤 Envoi instantané de la proposition

### Pour l'Admin (Page Sécurisée)
- 🔐 Accès protégé par mot de passe
- 📊 Tableau de bord avec statistiques
- 📋 Gestion des propositions (accepter/refuser)
- 📅 Calendrier des sessions programmées
- 📈 Vue d'ensemble des demandes en attente
- 📜 Historique complet des propositions

### Intégrations Disponibles
- ☁️ Google Sheets (synchronisation automatique)
- 🤖 Discord (notifications automatiques)
- 💾 Stockage local (pas besoin de base de données)

## 🚀 Installation Rapide

### Étape 1 : Télécharger
1. Téléchargez le fichier `game-proposals-app.html`
2. Ouvrez-le dans votre navigateur web

### Étape 2 : Configurer le mot de passe
1. Ouvrez `game-proposals-app.html` avec un éditeur de texte
2. Cherchez cette ligne :
```javascript
const ADMIN_PASSWORD = 'elbe2024';
```
3. Changez `'elbe2024'` par votre mot de passe
4. Sauvegardez le fichier

### Étape 3 : Utiliser l'application
- **Page publique** : Les joueurs peuvent proposer des sessions
- **Accès admin** : Cliquez sur "🔐 Accès Admin" et entrez votre mot de passe

## 🌐 Mise en Ligne

### Option 1 : GitHub Pages (Gratuit)
1. Créez un compte sur [GitHub.com](https://github.com)
2. Créez un nouveau repository (dépôt)
3. Uploadez le fichier en le renommant `index.html`
4. Activez GitHub Pages dans Settings → Pages
5. Votre URL : `https://votre-username.github.io/nom-repo`

### Option 2 : Netlify (Gratuit - Le plus simple)
1. Allez sur [Netlify.com](https://www.netlify.com)
2. Glissez-déposez le fichier HTML
3. Terminé ! Vous avez une URL instantanée

### Option 3 : Vercel (Gratuit)
1. Allez sur [Vercel.com](https://vercel.com)
2. Importez votre fichier
3. Déployez en un clic

## 📊 Intégration Google Sheets

Pour synchroniser les propositions avec Google Sheets, consultez le fichier `GUIDE_INTEGRATION.md` qui contient :
- Instructions détaillées pas à pas
- Code Google Apps Script prêt à l'emploi
- Configuration du webhook Discord
- Exemples de personnalisation

## 🎨 Personnalisation

### Changer les couleurs
Modifiez les couleurs du gradient dans le CSS :
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Ajouter un logo
Ajoutez cette ligne dans le header :
```html
<img src="VOTRE_LOGO.png" alt="Logo" style="max-width: 200px;">
```

### Modifier le titre
Changez "Elbe Gaming" par le nom de votre choix dans le HTML.

## 🔒 Sécurité

- ✅ Mot de passe protégé pour l'admin
- ✅ Les emails ne sont visibles que par les admins
- ✅ Pas de données sensibles dans l'URL
- ✅ Stockage local sécurisé dans le navigateur

**Note importante** : Pour une sécurité maximale en production, il est recommandé d'utiliser l'intégration Google Sheets avec authentification OAuth.

## 📱 Compatibilité

- ✅ Tous les navigateurs modernes (Chrome, Firefox, Safari, Edge)
- ✅ Responsive (fonctionne sur mobile et tablette)
- ✅ Pas besoin d'installation
- ✅ Pas besoin de serveur ou base de données

## 🆘 Aide et Support

### Problèmes courants

**Les données disparaissent après rafraîchissement**
- Solution : Utilisez l'intégration Google Sheets (voir GUIDE_INTEGRATION.md)

**Le mot de passe ne fonctionne pas**
- Vérifiez que vous avez bien modifié le mot de passe dans le code
- Videz le cache du navigateur (Ctrl+Shift+R)

**La page ne s'affiche pas correctement**
- Assurez-vous d'utiliser un navigateur récent
- Vérifiez qu'aucun bloqueur de publicité n'interfère

## 📦 Fichiers Inclus

- `game-proposals-app.html` - L'application complète (standalone)
- `GUIDE_INTEGRATION.md` - Guide complet pour Google Sheets et Discord
- `README.md` - Ce fichier

## 🎯 Utilisation Typique

### Scénario 1 : Joueur propose une session
1. Le joueur remplit le formulaire public
2. Il entre son pseudo, email, le jeu souhaité, date et horaire
3. Il clique sur "Envoyer la Proposition"
4. La proposition apparaît dans le tableau admin

### Scénario 2 : Admin gère les propositions
1. L'admin se connecte avec le mot de passe
2. Il voit toutes les propositions en attente sous forme de cartes
3. Il clique sur "✅ Accepter" ou "❌ Refuser"
4. Les sessions acceptées apparaissent dans le calendrier
5. (Optionnel) Discord envoie une notification au joueur

## 🔄 Mises à Jour Futures

L'application peut être étendue avec :
- Système de rappels automatiques
- Notifications par email
- Intégration Twitch
- Export Excel/PDF
- Multi-langues
- Application mobile

## 📄 Licence

Libre d'utilisation et de modification pour votre projet personnel ou commercial.

## 🙏 Remerciements

Créé pour aider les créateurs de contenu à mieux organiser leurs sessions de jeu avec leur communauté.

---

**Besoin d'aide ?** Consultez le `GUIDE_INTEGRATION.md` pour des instructions détaillées !

**Prêt à personnaliser ?** Tous les styles et textes peuvent être modifiés dans le fichier HTML !

Bon jeu ! 🎮🚀

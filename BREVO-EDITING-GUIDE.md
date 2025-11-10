# Guide complet : Éditer votre newsletter dans Brevo

Ce guide vous explique comment personnaliser entièrement votre newsletter (textes, images, couleurs, fond) directement dans l'interface de Brevo.

---

## 📋 Table des matières

1. [Importer la newsletter dans Brevo](#1-importer-la-newsletter-dans-brevo)
2. [Éditer les textes](#2-éditer-les-textes)
3. [Modifier les images](#3-modifier-les-images)
4. [Changer les couleurs](#4-changer-les-couleurs)
5. [Personnaliser le fond](#5-personnaliser-le-fond)
6. [Conseils et bonnes pratiques](#6-conseils-et-bonnes-pratiques)

---

## 1. Importer la newsletter dans Brevo

### Étape 1 : Connexion à Brevo
1. Connectez-vous à votre compte Brevo : [https://app.brevo.com](https://app.brevo.com)
2. Allez dans **Campaigns** → **Email Campaigns**
3. Cliquez sur **Create a campaign**

### Étape 2 : Utiliser votre template HTML
1. Choisissez **Paste your HTML code**
2. Ouvrez le fichier `index.html` dans un éditeur de texte
3. Copiez tout le contenu (Ctrl+A puis Ctrl+C)
4. Collez le code dans l'éditeur Brevo
5. Cliquez sur **Next**

### Étape 3 : Passer en mode édition
- Brevo vous montrera un aperçu de votre newsletter
- Vous pouvez maintenant cliquer sur n'importe quel élément pour le modifier

---

## 2. Éditer les textes

### Textes modifiables dans la newsletter

#### **Header (En-tête)**
- **Date** : `NOVEMBRE 2025`
  - Cliquez dessus pour changer le mois/année
- **Liens** : `VISUALISER SUR LE WEB` | `S'ABONNER`
  - Cliquez pour modifier le texte
  - Double-cliquez pour changer le lien (URL)

#### **Badge du logo**
- **Texte** : `C'EST LA NEWSLETTER`
  - Cliquez pour personnaliser le message

#### **Titre Edito**
- **Titre** : `Edito`
  - Cliquez pour changer le titre de cette section

#### **Texte Edito**
- **Paragraphe** : Lorem ipsum…
  - Cliquez dans le bloc de texte pour le remplacer par votre contenu
  - Formatage : gras, italique, liens disponibles dans la barre d'outils Brevo

#### **Titre "Les nouveautés"**
- **Titre** : `Les nouveautés`
  - Cliquez pour personnaliser

#### **Textes des deux cartes news**
- **Carte gauche/droite** : Deux paragraphes modifiables
  - Cliquez sur chaque texte pour le modifier

#### **Bouton CTA**
- **Texte** : `VISITER NOTRE COMPTE INSTA`
  - Cliquez pour changer le texte
  - Double-cliquez pour modifier le lien vers votre Instagram

#### **Titre "Quoi d'autres ?"**
- **Titre** : `Quoi d'autres ?`
  - Cliquez pour personnaliser

#### **Article en colonnes**
- **Texte** : Hipster ipsum… / Crypto ipsum…
  - Cliquez dans le bloc de texte pour remplacer

#### **Titre "Un gros titre"**
- **Titre** : `Un gros titre`
  - Cliquez pour personnaliser

#### **Footer (Pied de page)**
- **Texte principal** :
  - `Inscrivez-vous à notre newsletter ici.`
  - `Vous pouvez vous désabonner ici.`
  - `Cette newsletter est préparée par....`
  - Cliquez pour modifier chaque phrase
  - Les liens sont déjà en gras et soulignés — changez les URLs en double-cliquant
- **Crédits photos** : `Crédits photos : ©`
  - Ajoutez vos crédits après le ©

### Comment éditer du texte dans Brevo
1. **Simple clic** : Sélectionne le bloc de texte
2. **Double clic** : Ouvre l'éditeur de texte enrichi
3. Utilisez la barre d'outils pour :
   - Gras, italique, souligné
   - Changer la taille de la police
   - Ajouter/modifier des liens
   - Changer l'alignement

---

## 3. Modifier les images

### 📷 Liste des images dans la newsletter

| Emplacement | Nom du fichier actuel | Description |
|-------------|----------------------|-------------|
| **Header** | `logo.png` | Logo principal com'art |
| **Edito** | `picture-1.png` | Image masquée en trois formes arrondies |
| **Edito underline** | `underline.png` | Trait violet sous le titre |
| **News - Gauche** | `burger.png` | Image burger |
| **News - Droite** | `picture-2.png` | Portrait |
| **CTA icon** | `arrow-right.svg` | Flèche circulaire violette |
| **Article** | `picture-2.png` | Image grande section "Quoi d'autres ?" |
| **Final** | `picture-2.png` | Image grande section finale |
| **Footer** | `logo-footer.png` | Logo en pied de page |
| **Socials** | `instagram.png`, `facebook.png` | Icônes réseaux sociaux |

### Comment uploader et changer une image dans Brevo

#### Méthode 1 : Upload direct
1. **Cliquez sur l'image** que vous voulez remplacer
2. Dans le panneau de droite, cliquez sur **Replace image** ou **Upload**
3. Sélectionnez votre nouvelle image sur votre ordinateur
4. Brevo upload automatiquement et remplace l'image

#### Méthode 2 : Utiliser la bibliothèque Brevo
1. Allez dans **Content** → **Image gallery** dans le menu principal Brevo
2. Uploadez toutes vos images à l'avance
3. Dans l'éditeur de newsletter, cliquez sur une image
4. Choisissez **Select from gallery**
5. Sélectionnez votre image dans la galerie

#### Méthode 3 : URL externe (recommandé pour la production)
1. Uploadez vos images sur votre serveur ou un CDN
2. Copiez l'URL complète (ex: `https://votre-site.com/images/logo.png`)
3. Dans le code HTML du template :
   - Recherchez `src="images/logo.png"`
   - Remplacez par `src="https://votre-site.com/images/logo.png"`
4. Répétez pour toutes les images

### ✅ Bonnes pratiques pour les images
- **Format** : PNG (logos/transparence), JPG (photos)
- **Taille max recommandée** : 600px de largeur pour les images pleines largeur
- **Poids** : Optimisez vos images (max 200-300 KB chacune)
- **Nommage** : Utilisez des noms clairs sans espaces (`mon-image.jpg`)

---

## 4. Changer les couleurs

### 🎨 Palette de couleurs actuelle

| Élément | Couleur actuelle | Code hexadécimal |
|---------|------------------|------------------|
| **Fond principal** | Vert pastel clair | `#ECFFBB` |
| **Violet (accents)** | Violet vif | `#612ffe` |
| **Texte principal** | Noir doux | `#333` |
| **Fond logo** | Blanc cassé | `#faf8fd` |
| **Liens footer** | Noir foncé | `#111` |

### Comment modifier les couleurs

#### Option 1 : Rechercher-Remplacer (recommandé pour changer toutes les occurrences)
1. Dans l'éditeur HTML de Brevo, cliquez sur **</> Source code**
2. Utilisez la fonction **Rechercher** (Ctrl+F)
3. Recherchez le code couleur à remplacer, par exemple : `#ECFFBB`
4. Utilisez **Remplacer tout** avec votre nouvelle couleur (ex: `#FFE5E5` pour un rose pastel)
5. Répétez pour chaque couleur que vous voulez changer

#### Option 2 : Modifier section par section
1. Cliquez sur un élément (bouton, fond, texte)
2. Dans le panneau de propriétés à droite, cherchez **Background color** ou **Text color**
3. Sélectionnez une nouvelle couleur via le sélecteur de couleur
4. Validez

### Exemples de modifications courantes

#### Changer le fond de vert à bleu pastel
- Rechercher : `#ECFFBB`
- Remplacer par : `#BBE5FF`

#### Changer le violet à orange
- Rechercher : `#612ffe`
- Remplacer par : `#FF6B35`

#### Changer la couleur du texte
- Rechercher : `color: #333`
- Remplacer par : `color: #000` (noir pur) ou `color: #555` (gris moyen)

---

## 5. Personnaliser le fond

### Fond actuel
- **Couleur** : `#ECFFBB` (vert pastel clair)
- **Appliqué à** : `.wrapper`, `.container`, toutes les sections

### Comment changer le fond global

#### Méthode rapide (Rechercher-Remplacer)
1. Allez dans **</> Source code**
2. Recherchez : `background-color: #ECFFBB;`
3. Remplacez par votre couleur : `background-color: #FFFFFF;` (blanc) ou autre
4. Cliquez **Replace all** pour appliquer partout

#### Méthode précise (modifier le CSS)
1. Dans le code source, localisez la section `<style>` en haut du fichier
2. Cherchez les classes suivantes et modifiez `background-color` :

```css
.wrapper {
    background-color: #ECFFBB; /* ← Changez ici */
}

.container {
    background-color: #ECFFBB; /* ← Changez ici */
}

.header {
    background-color: #ECFFBB; /* ← Changez ici */
}

.edito-section {
    background-color: #ECFFBB; /* ← Changez ici */
}

.news-section {
    background-color: #ECFFBB; /* ← Changez ici */
}

.footer {
    background-color: #ECFFBB; /* ← Changez ici */
}
```

### Appliquer un fond dégradé (avancé)
Remplacez `background-color` par `background` avec un dégradé :

```css
.wrapper {
    background: linear-gradient(180deg, #ECFFBB 0%, #FFFFFF 100%);
}
```

### Appliquer une image de fond (avancé)
```css
.wrapper {
    background-image: url('https://votre-cdn.com/fond.jpg');
    background-size: cover;
    background-position: center;
}
```

---

## 6. Conseils et bonnes pratiques

### ✅ Avant d'envoyer votre newsletter

#### Testez sur plusieurs clients email
- **Gmail** (web et app mobile)
- **Outlook** (Windows, Mac, web)
- **Apple Mail** (iPhone, iPad, Mac)
- **Thunderbird**, **Yahoo Mail**, etc.

Brevo propose un **Test mode** :
1. Cliquez sur **Send a test**
2. Entrez vos adresses email de test
3. Vérifiez l'affichage sur chaque client

#### Vérifiez les liens
- Testez chaque lien (header, footer, CTA, images)
- Assurez-vous que les URLs sont correctes
- Vérifiez les liens de désinscription

#### Optimisez les images
- Compressez vos images avec [TinyPNG](https://tinypng.com) ou [Squoosh](https://squoosh.app)
- Utilisez des formats adaptés (PNG pour logos, JPG pour photos)
- Vérifiez que toutes les images chargent rapidement

#### Personnalisez avec les variables Brevo
Brevo permet d'insérer des variables dynamiques :
- `{{ contact.FIRSTNAME }}` : Prénom du destinataire
- `{{ contact.LASTNAME }}` : Nom
- `{{ contact.EMAIL }}` : Email

Exemple dans votre template :
```html
<p>Bonjour {{ contact.FIRSTNAME }},</p>
```

### 🎯 Astuces d'édition Brevo

#### Prévisualisation responsive
- Cliquez sur l'icône **mobile/desktop** en haut pour voir le rendu sur mobile
- Le template est déjà responsive (s'adapte automatiquement)

#### Sauvegarder régulièrement
- Brevo sauvegarde automatiquement, mais cliquez sur **Save** régulièrement
- Vous pouvez créer des versions : **Save as template** pour réutiliser

#### Dupliquer pour tester
- Avant de faire de gros changements, dupliquez votre campagne
- Testez sur la copie avant de modifier l'original

#### Mode code vs mode visuel
- **Mode visuel** : Cliquez directement sur les éléments (plus simple)
- **Mode code** (`</>`) : Contrôle total du HTML/CSS (pour utilisateurs avancés)
- Alternez entre les deux selon vos besoins

### 🚀 Workflow recommandé

1. **Préparez vos contenus** :
   - Textes dans un document Word/Google Docs
   - Images optimisées dans un dossier
   - Palette de couleurs définie (codes hex notés)

2. **Uploadez les images** :
   - Allez dans **Image gallery** de Brevo
   - Uploadez toutes vos images
   - Notez leurs URLs Brevo

3. **Remplacez les textes** :
   - Copiez-collez vos textes finaux
   - Vérifiez la mise en forme (gras, liens, etc.)

4. **Changez les couleurs** :
   - Utilisez Rechercher-Remplacer pour les couleurs globales
   - Ajustez les couleurs spécifiques en mode visuel

5. **Remplacez les images** :
   - Cliquez sur chaque image et sélectionnez la nouvelle depuis la galerie

6. **Testez** :
   - Envoyez-vous un test
   - Vérifiez sur mobile et desktop
   - Corrigez si nécessaire

7. **Envoyez** :
   - Planifiez l'envoi ou envoyez immédiatement
   - Suivez les statistiques d'ouverture et de clics

---

## 📞 Support

### Ressources Brevo
- Documentation officielle : [https://help.brevo.com](https://help.brevo.com)
- Support Brevo : Contactez via le chat dans votre interface

### Problèmes courants

#### "Mes images ne s'affichent pas"
- Vérifiez que les URLs sont correctes et accessibles
- Uploadez les images dans Brevo Image Gallery
- Testez les liens images dans un navigateur

#### "Les couleurs ne changent pas"
- Certains clients email ignorent le CSS — utilisez des couleurs inline autant que possible
- Testez avec le mode test de Brevo

#### "Le design est cassé sur Outlook"
- Outlook utilise Word pour rendre les emails (limitations)
- Le template est optimisé mais certaines fonctionnalités avancées (SVG, certains CSS) peuvent ne pas fonctionner
- Envisagez des images PNG de secours pour les éléments critiques

---

## 🎉 Vous êtes prêt !

Votre newsletter est maintenant entièrement personnalisable dans Brevo. N'hésitez pas à expérimenter et à sauvegarder plusieurs versions pour comparer.

**Bon envoi ! 📧**

# Guide d'édition de la Newsletter Com'art

## Introduction

Ce guide explique comment personnaliser la newsletter Com'art dans l'interface Brevo (Mailinblue). Vous apprendrez à modifier les couleurs, les polices, les images et les icônes.

## Modification des couleurs

### Couleurs de fond des sections

Chaque section de la newsletter a une couleur de fond définie dans les styles inline :

- **Fond vert clair** (`#ecffbb`) : Utilisé pour la plupart des sections
- **Fond violet** (`#5E2BFF`) : Utilisé pour la section "Les nouveautés"

Pour changer ces couleurs :

1. Dans l'éditeur Brevo, sélectionnez la section souhaitée
2. Cliquez sur "Modifier le style" ou "Background"
3. Choisissez la nouvelle couleur
4. Ou modifiez directement le code HTML : `background-color: #nouvelle_couleur;`

### Couleurs du texte

Les couleurs de texte sont définies dans les balises `<span>`, `<p>`, `<h1>`, etc. :

- **Texte noir** (`#000`) : Texte principal
- **Texte blanc** (`#fff`) : Texte sur fond violet

Pour changer :

1. Sélectionnez le texte dans l'éditeur Brevo
2. Utilisez l'outil de couleur du texte
3. Ou modifiez `color: #nouvelle_couleur;` dans le code

### Couleurs des boutons et éléments décoratifs

- **Bordures** (`#333`) : Bordures des boutons
- **Fond des boutons** (`#faf8fd`) : Fond blanc cassé

## Modification des polices

### Familles de polices

La newsletter utilise deux familles de polices principales :

- **Roboto** : Pour le texte courant (`font-family: 'Roboto', Arial, sans-serif;`)
- **Futura Std** : Pour les titres (`font-family: 'Futura Std', Arial, sans-serif;`)

Pour changer les polices :

1. Dans l'éditeur Brevo, sélectionnez le texte
2. Choisissez une nouvelle police dans le menu des polices
3. Ou modifiez `font-family: 'Nouvelle Police', Arial, sans-serif;` dans le code

### Tailles de police

- **Titres principaux** : `font-size: 48px;`
- **Sous-titres** : `font-size: 28px;` (mobile)
- **Texte normal** : `font-size: 13px;` ou `font-size: 16px;`

### Styles de police

- **Gras** : `font-weight: 700;` ou `font-weight: bold;`
- **Normal** : `font-weight: 400;`
- **Italique** : `font-style: italic;`

## Modification des images et icônes

### Remplacement d'images dans Brevo

#### Images principales (héros, articles, etc.)

1. Dans l'éditeur Brevo, cliquez sur l'image à remplacer
2. Cliquez sur "Changer l'image" ou "Upload"
3. Sélectionnez une nouvelle image depuis votre ordinateur
4. Ou choisissez une image de votre bibliothèque de contenu Brevo

#### Images du logo et des icônes

Les images sont hébergées sur le CDN Brevo avec des URLs comme :

```
https://img.mailinblue.com/10162090/images/content_library/original/69124c5fab9a673adbebd93e.png
```

Pour remplacer :

1. Allez dans "Contenu" > "Bibliothèque de contenu" dans Brevo
2. Upload de nouvelles images
3. Copiez les nouvelles URLs
4. Remplacez les URLs dans le code HTML ou utilisez l'éditeur visuel

### Icônes des réseaux sociaux

Les icônes Instagram et Facebook sont situées dans le pied de page :

```html
<img
  src="https://img.mailinblue.com/10162090/images/content_library/original/6911eeb6815afb1faab3f754.png"
  alt="Instagram" />
<img
  src="https://img.mailinblue.com/10162090/images/content_library/original/6911eeb6ffddcb3dad0cc094.png"
  alt="Facebook" />
```

Pour changer :

1. Upload de nouvelles icônes dans la bibliothèque de contenu
2. Remplacez les URLs dans le code
3. Assurez-vous que les icônes font 30x30 pixels pour la cohérence

### Image de fond violet

L'image de fond de la section "Les nouveautés" est définie dans :

```html
background-image:
url('https://img.mailinblue.com/10162090/images/content_library/original/69124f81394699ea4fd4acb3.png');
```

Pour changer :

1. Upload une nouvelle image de fond (recommandé : 600x607px)
2. Remplacez l'URL dans les styles CSS
3. Pour Outlook, mettez aussi à jour l'URL dans le code VML

## Conseils pour l'édition

### Responsive Design

La newsletter est optimisée pour mobile avec des media queries :

- **Desktop** : Largeur 600px
- **Mobile** : Largeur 100% avec padding de 16px

### Compatibilité email

- Utilisez toujours des fallbacks (Arial, sans-serif)
- Préférez les couleurs hexadécimales (#ecffbb)
- Testez dans différents clients email (Gmail, Outlook, etc.)

### Structure des sections

- **Header** (row-1) : Logo et navigation
- **Édito** (row-2) : Image héros et titre
- **Titre "Les nouveautés"** (row-3)
- **Section violette** (row-4) : Articles avec fond coloré
- **Bouton Instagram** (row-4b) : CTA séparé
- **Icônes** (row-5) : Section décorative
- **Article** (row-6) : Contenu principal
- **Gros titre** (row-7)
- **Article final** (row-8)
- **Logo footer** (row-9)
- **Footer** (row-10) : Liens et réseaux sociaux

## Test et validation

Après chaque modification :

1. Prévisualisez la newsletter dans Brevo
2. Envoyez un test à différentes adresses email
3. Vérifiez l'affichage sur mobile et desktop
4. Testez dans Gmail, Outlook et Apple Mail

## Support

Pour plus d'aide, consultez la documentation Brevo ou contactez le support technique.

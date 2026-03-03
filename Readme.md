# Agro – Modern Farming Website

## Présentation

Ce projet consiste à reproduire la landing page “Agro – Modern Farming Website” trouvé sur **"https://dribbble.com/shots/27138832-Agro-Modern-Farming-Website"** avec Tailwind.

L’objectif était de respecter :

- La structure HTML sémantique
- Les principes d’ergonomie
- Le responsive mobile first
- L’accessibilité minimale

## Structure de la page

La page est organisée avec :

- header (logo + navigation)
- main
  - Section Hero
  - Section Trusted by
  - Section About
- footer

## Ergonomie

### Hiérarchie visuelle

Le titre principal.  
Les CTA sont placés juste en dessous pour guider l’utilisateur.  
La carte à droite attire l’œil.

### Pattern de lecture

La page suit un pattern en Z dans le Hero :

- Logo en haut à gauche
- Menu en haut à droite
- Titre à gauche
- Carte à droite

### Charge cognitive

- Seulement 2 boutons principaux
- Sections bien séparées
- Espacements cohérents
- Pas de surcharge d’informations

## Accessibilité

- HTML sémantique
- alt sur les images
- Focus visible sur les boutons
- Menu mobile utilisable au clavier
- Fermeture du menu avec la touche Escape
- Contrastes lisibles

## Choix techniques Tailwind

Le projet utilise Tailwind v4 en mode CSS-first :

- @import "tailwindcss"
- Palette personnalisée avec @theme
- Police personnalisée
- Utilitaires personnalisés avec @utility (boutons, glass, container)

Le responsive est mobile-first :

- Version mobile par défaut
- Adaptation en desktop avec lg:grid-cols-2

## Difficultés

- Gérer le menu burger proprement
- Adapter les espacements pour être fidèle au design
- Comprendre le fonctionnement des utilitaires personnalisés

## Conclusion

J'ai apris :

- La logique utility-first de Tailwind
- L’importance de la structure HTML
- Comment rendre une page responsive proprement
- Les bases de l’accessibilité

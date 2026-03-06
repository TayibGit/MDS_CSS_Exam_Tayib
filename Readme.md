# Agro – Modern Farming Website

## Présentation

Ce projet consiste à reproduire la landing page "Agro – Modern Farming Website" trouvée sur **[Dribbble](https://dribbble.com/shots/27138832-Agro-Modern-Farming-Website)** avec Tailwind CSS v4.

L'objectif était de respecter :

- La structure HTML sémantique
- Les principes d'ergonomie
- Le responsive mobile first
- L'accessibilité minimale

## Structure de la page

La page est organisée avec :

- `header` — logo + navigation desktop + menu burger mobile
- `main`
  - Section Hero
  - Section Trusted by
  - Section About
  - Section Pricing
  - Section Contact
- `footer`

## Ergonomie

### Hiérarchie visuelle

Le titre principal guide le regard. Les CTA sont placés juste en dessous pour orienter l'utilisateur. La carte produit à droite attire l'œil secondaire.

### Pattern de lecture

La page suit un pattern en Z dans le Hero :

- Logo en haut à gauche
- Menu en haut à droite
- Titre à gauche
- Carte à droite

## Accessibilité

- HTML sémantique (`header`, `main`, `footer`, `nav`, `article`, `form`)
- Attributs `alt` sur toutes les images
- Focus visible sur les éléments interactifs
- Menu mobile entièrement utilisable au clavier
- Fermeture du menu avec la touche `Escape`
- Piège de focus dans le menu mobile (`trapFocus`)
- Contrastes lisibles
- Labels associés aux champs de formulaire

## Sections

### Pricing

Trois plans tarifaires (Starter, Professional, Enterprise) présentés en grille 3 colonnes. Chaque carte liste les fonctionnalités incluses avec un CTA vers le formulaire de contact.

### Contact

Formulaire de contact avec champs Nom, Email et Message. Les informations de contact (email, téléphone) sont affichées à gauche du formulaire.

### Footer

Trois colonnes : présentation de la marque, liens de navigation, et CTA vers la section Pricing.

## Choix techniques Tailwind

Le projet utilise Tailwind v4 en mode CSS-first :

- `@import "tailwindcss"`
- Palette personnalisée avec `@theme`
- Police personnalisée
- Utilitaires personnalisés avec `@utility` : `btn-accent`, `btn-ghost`, ...

Le responsive est mobile-first :

- Version mobile par défaut
- Adaptation pc avec `lg:grid-cols-2` et `lg:grid-cols-3`

## Difficultés

- Gérer le menu burger proprement
- Adapter les espacements pour être fidèle au design
- Comprendre le fonctionnement des utilitaires personnalisés avec `@utility`

## Conclusion

Ce projet m'a permis d'apprendre :

- La logique utility-first de Tailwind
- L'importance de la structure HTML sémantique
- Comment rendre une page responsive proprement
- La configuration avancée de Tailwind v4 (`@theme`, `@utility`)

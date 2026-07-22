# Murpierre — murpierre.com

Site vitrine de Murpierre, entreprise de vente et pose de pierre naturelle de
parement mural.

## Contenu

- `index.html` — page d'accueil (héro, sélections, avantages, références,
  histoire, showroom, contact)
- `mentions-legales.html` — mentions légales (champs à compléter avec les
  informations de l'entreprise : SIRET, hébergeur, etc.)
- `404.html` — page d'erreur personnalisée (servie par GitHub Pages)
- `css/style.css` — feuille de style unique
- `assets/` — image de partage réseaux sociaux (og-image) et icônes
- `robots.txt` / `sitemap.xml` — référencement (SEO)
- `CNAME` — domaine personnalisé pour GitHub Pages

## SEO

Le site inclut : titres et descriptions optimisés, URL canoniques, balises
Open Graph et Twitter Card avec image de partage, données structurées
schema.org (`HomeAndConstructionBusiness`), sitemap XML et robots.txt.
Après la mise en ligne, penser à déclarer le site dans Google Search Console
et à y soumettre `sitemap.xml`. Les données structurées (téléphone, adresse,
horaires) sont à mettre à jour en même temps que la section Contact.

Site 100 % statique : aucun outil de build, aucune dépendance. Les visuels sont
des SVG intégrés, à remplacer par de vraies photos de chantiers quand elles
seront disponibles.

## Mise en ligne (gratuite, via GitHub Pages)

1. Dans les réglages du dépôt, ouvrir **Settings → Pages**.
2. Choisir la branche à publier (« Deploy from a branch », dossier `/`).
3. Chez le registrar du domaine `murpierre.com`, faire pointer le domaine vers
   GitHub Pages (enregistrements `A`/`ALIAS` ou `CNAME` selon la documentation
   GitHub) — le fichier `CNAME` du dépôt est déjà en place.
4. Activer « Enforce HTTPS » une fois le certificat émis.

## À personnaliser

- Numéro de téléphone, adresse et horaires dans la section Contact et dans les
  mentions légales (valeurs fictives pour l'instant).
- Tarifs indicatifs des pierres dans la section « Nos pierres ».
- Le formulaire de contact utilise `mailto:` pour rester sans serveur ; pour un
  vrai envoi de formulaire, brancher un service type Formspree ou équivalent.

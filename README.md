# Murpierre — murpierre.com

Site vitrine de Murpierre, entreprise de vente et pose de pierre naturelle de
parement mural.

## Contenu

- `index.html` — page d'accueil (héro, gamme de pierres, avantages,
  réalisations, à propos, contact)
- `mentions-legales.html` — mentions légales (champs à compléter avec les
  informations de l'entreprise : SIRET, hébergeur, etc.)
- `css/style.css` — feuille de style unique
- `CNAME` — domaine personnalisé pour GitHub Pages

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

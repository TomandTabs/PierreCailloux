# Murpierre — murpierre.com

Site vitrine de **Murpierre · Pierres de Kern**, spécialiste des pierres
naturelles pour murs, sols et pièces sur mesure, à **Martigny (Valais)**.

Identité artisanale & patrimoniale, devise *« La pierre à votre mesure »*,
métaphore du **cairn** (empilement de pierres qui sert de repère en montagne).

## Contenu

- `index.html` — page d'accueil : hero, bandeau de confiance, collections,
  réalisations, notre histoire (colophon sombre), sur mesure, catalogues, contact
- `mentions-legales.html` — mentions légales (champs à compléter : IDE/CHE,
  TVA, hébergeur…)
- `404.html` — page d'erreur personnalisée (servie par GitHub Pages)
- `css/style.css` — feuille de style unique, basée sur le design system
  « Classical » (tokens couleurs / typo / espacement)
- `assets/` — illustrations de pierre (SVG), image de partage (og-image),
  icônes
- `robots.txt` / `sitemap.xml` — référencement (SEO)
- `CNAME` — domaine personnalisé pour GitHub Pages

## Identité graphique

Issue du hand-off design (dossier « Identité graphique Murpierre ») :

- **Couleurs** : papier `#f3f2f2`, encre `#201f1d`, noir d'ardoise `#1b1917`,
  **Or de Kern `#b68235`** (utilisé en trait, filet, soulignement — jamais en
  aplat de texte courant).
- **Typographies** : *Cormorant Garamond* (titres, en régulier 400 pour
  l'affichage) + *Lora* (texte courant). Chargées via Google Fonts.
- **Logo « cairn »** : empilement de 5 pierres, contour or sans remplissage
  (SVG inline dans la nav, le pied de page, la bande catalogues et en filigrane
  dans la section « Notre histoire »). Sert aussi de favicon.
- **Traitement image `.plate`** : chaque photo est « tipée » comme une planche
  de livre (grain sépia chaud + passe-partout clair).

## Images

Les visuels sont pour l'instant des **illustrations SVG** de pierre
(`assets/stone-*.svg`), pensées comme emplacements. À remplacer par les vraies
photographies du client (murs, sols, réalisations, atelier/showroom) en
conservant le traitement `.plate` et les ratios d'origine.

## SEO

Titres et descriptions optimisés, URL canoniques, balises Open Graph et Twitter
Card avec image de partage, données structurées schema.org
(`HomeAndConstructionBusiness`, adresse à Martigny), sitemap XML et robots.txt.
Après la mise en ligne : déclarer le site dans Google Search Console et y
soumettre `sitemap.xml`. Mettre à jour les données structurées (téléphone,
adresse, horaires) en même temps que la section Contact.

Site 100 % statique : aucun outil de build, aucune dépendance.

## Mise en ligne (gratuite, via GitHub Pages)

1. Dans les réglages du dépôt, ouvrir **Settings → Pages**.
2. Choisir la branche à publier (« Deploy from a branch », dossier `/`).
3. Chez le registrar du domaine `murpierre.com`, faire pointer le domaine vers
   GitHub Pages — le fichier `CNAME` du dépôt est déjà en place.
4. Activer « Enforce HTTPS » une fois le certificat émis.

## À personnaliser

- Coordonnées : téléphone `+41 27 000 00 00`, adresse `Rue Exemple 1, 1920
  Martigny` et horaires sont des **valeurs fictives** à remplacer (section
  Contact, mentions légales et données structurées).
- Liens réseaux sociaux (Instagram, Pinterest, LinkedIn) à brancher.
- Catalogues PDF à fournir et à lier depuis la bande « Catalogues ».
- Le formulaire utilise `mailto:` pour rester sans serveur ; pour un vrai envoi,
  brancher un service type Formspree ou équivalent.

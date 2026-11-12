# Anemo — informations légales

Pages légales publiques de l'application **Anemo Memory Aid**, servies via GitHub Pages.

Ce dépôt est public **uniquement** parce que Google Play et l'App Store exigent des URL
accessibles sans authentification. Le code source de l'application reste privé.

| Page | Fichier |
|---|---|
| Accueil | `index.html` |
| Politique de confidentialité | `confidentialite.html` |
| Suppression de compte | `suppression-compte.html` |
| Conditions générales | `conditions.html` |
| Mentions légales | `mentions-legales.html` |

`conditions.html` et `confidentialite.html` sont générées depuis `src/content/legalTerms.ts`
du dépôt de l'application (`node scripts/site-legal/generer.ts <ce dossier>`) : ne pas les
modifier à la main.

Toute modification est publiée automatiquement par GitHub Pages.

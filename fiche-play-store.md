# Fiche Play Store — Anemo

## Nom de l'application (30 caractères max)

```
Anemo — Souvenirs de vie
```

> Le nom déclaré dans l'app est « Anemo Memory Aid ». Sur le Play Store français,
> un nom en français est mieux compris et mieux référencé. Les deux peuvent différer.

---

## Description courte (80 caractères max)

```
Racontez vos souvenirs à voix haute. Anemo les transcrit et les organise.
```

Variante si tu veux insister sur la transmission familiale :

```
Vos souvenirs racontés à voix haute, transcrits et transmis à vos proches.
```

---

## Description complète (4000 caractères max)

```
Vos souvenirs méritent mieux qu'un carnet oublié dans un tiroir.

Anemo vous permet de raconter votre vie à voix haute. Vous appuyez sur un bouton, vous parlez comme vous le feriez à un proche assis en face de vous. L'application se charge du reste.


CONÇUE POUR ÊTRE SIMPLE

Un seul grand bouton. Pas de menu compliqué, pas de réglage à comprendre. Vous appuyez, vous racontez, vous appuyez à nouveau pour terminer. Le texte est grand, les couleurs sont contrastées, et chaque écran ne fait qu'une seule chose.


VOS MOTS DEVIENNENT UN RÉCIT

Chaque enregistrement est transcrit automatiquement. Vous n'avez rien à taper.

Anemo repère ensuite les personnes dont vous parlez, les lieux que vous évoquez, les époques et les émotions de votre récit. Elle reconstitue le fil de votre histoire, même si vous l'avez racontée en plusieurs fois et dans le désordre.

Si une transcription comporte une erreur, vous pouvez la corriger d'un geste.


DES QUESTIONS POUR ALLER PLUS LOIN

Après chaque souvenir, Anemo vous propose quelques questions simples : qui était là, à quoi ressemblait l'endroit, ce que vous avez ressenti ce jour-là.

Ce sont ces questions qui font surgir les détails qu'on croyait oubliés — et qui transforment une anecdote en véritable récit.


À PARTAGER AVEC CEUX QUE VOUS AIMEZ

Vous pouvez inviter vos enfants, vos petits-enfants ou vos proches à rejoindre un souvenir. Chacun ajoute sa propre voix, ses propres détails, et l'histoire se construit à plusieurs.

Un mariage, un déménagement, un été d'enfance : chacun s'en souvient autrement, et Anemo réunit ces versions.


CE QUI RESTE PRIVÉ

Vos enregistrements vous appartiennent. Ils ne sont jamais vendus, jamais utilisés à des fins publicitaires, et ne servent jamais à entraîner des intelligences artificielles.

L'application ne contient aucune publicité et aucun traceur.

Vous pouvez exporter toutes vos données ou supprimer votre compte à tout moment, directement depuis l'application.


COMMENT COMMENCER

L'offre gratuite vous permet d'enregistrer vos premiers souvenirs et de découvrir l'application sans rien payer.

Les formules payantes lèvent les limites d'enregistrement pour celles et ceux qui souhaitent raconter davantage.


Anemo a été pensée pour les personnes âgées, mais elle s'adresse à quiconque veut garder une trace de ce qui compte : un parent qui raconte son enfance, une grand-mère qui décrit son village, un père qui explique enfin pourquoi il a choisi ce métier.

Les souvenirs ne se perdent pas d'un coup. Ils s'effacent doucement, faute d'avoir été dits.

Commencez aujourd'hui.
```

---

## Catégorie et classification

| Champ | Valeur |
|---|---|
| Catégorie | **Style de vie** |
| Tags | Souvenirs, Famille, Journal, Dictaphone |
| Classification du contenu | Tout public |
| Audience cible | **18 ans et plus** |
| Publicités | Non |
| Achats intégrés | Oui |

---

## Visuels à produire

| Élément | Format | État |
|---|---|---|
| Icône | 512 × 512 PNG | ✅ `store-assets/play/icon-512.png` |
| Image de mise en avant | 1024 × 500 PNG | ✅ `store-assets/play/feature-graphic-1024x500.png` |
| Captures téléphone | 4 minimum, 1080 × 1920 | ⬜ à prendre sur appareil réel |

Les deux premiers sont générés par `python3 store-assets/generate.py`, dans le dépôt
de l'application. Le même script corrige l'icône adaptative Android, qui reprenait
l'icône iOS en plein cadre et se faisait rogner par tous les lanceurs.

> Quatre captures en 1080 × 1080 sont exigées pour être éligible aux mises en avant
> de Google. Deux suffisent pour publier.

Captures recommandées, dans l'ordre :
1. L'écran d'accueil avec le grand bouton micro — c'est la promesse de simplicité
2. Un enregistrement en cours, chronomètre visible
3. Une synthèse : personnes, lieux, émotions
4. Les questions de relance

# CLAUDE.md

<!-- Ce fichier est lu par l'agent au début de chaque session. Gardez-le court : chaque ligne coûte des tokens à chaque échange. On y met ce que l'agent ne peut pas deviner en lisant le code. -->

Projet <nom>. Lire BRIEF.md avant toute modification de périmètre.

## Stack
<!-- Langages, frameworks, hébergement, et où se trouve quoi. Exemple : appli web statique dans app/web, fonctions serverless dans netlify/functions. -->

## Règles
<!-- Les règles qui ne se discutent pas. Exemples : -->
- Outils simples et prévisibles. Le raisonnement reste au modèle.
- Toute fonction qui appelle une API accepte un client injectable, pour les tests.
- Jamais de clé ni de jeton dans le code ni dans Git. Ils vivent dans un fichier .env ignoré, ou dans les variables de l'hébergeur.
- Pas de scraping. Uniquement des API publiques.
- Langue et ton des textes de l'interface.

## Commandes
<!-- Installer, tester, lancer en local. L'agent les utilisera telles quelles. -->

## Design
<!-- Figé une fois la direction visuelle validée : couleurs avec leurs codes, polices, rayons, icônes, ton, règles d'accessibilité. Tous les écrans s'y conforment. -->

## Leçons apprises
<!-- La section la plus précieuse. Chaque erreur corrigée devient une règle d'une ligne, pour ne pas la refaire. Exemple : « Les tests simulés doivent copier une vraie réponse d'API, pas un format supposé. » -->

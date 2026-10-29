# Check-list avant mise en ligne

À passer avant chaque ouverture au public, puis à chaque nouvelle donnée collectée ou nouveau service tiers.

## Sécurité
- [ ] Aucune clé, aucun jeton, aucun mot de passe dans le code ni dans l'historique Git.
- [ ] Les clés vivent dans les variables d'environnement de l'hébergeur, avec le moins de droits possible.
- [ ] Les appels aux API payantes ou limitées passent par une fonction serveur, jamais depuis le navigateur.
- [ ] Les entrées utilisateur sont vérifiées côté serveur.
- [ ] En-têtes de sécurité posés (Content-Security-Policy, HTTPS forcé).
- [ ] Quotas des API connus, mise en cache des réponses pour les respecter.
- [ ] Dépendances à jour, revue du code par un agent dédié puis relecture humaine.

## RGPD et vie privée
- [ ] Liste des données traitées, et pour chacune la raison et la durée de conservation.
- [ ] Le moins de données possible. Pas de compte si l'usage n'en a pas besoin.
- [ ] Pas de cookie ni de traceur publicitaire, ou alors un consentement explicite.
- [ ] Position arrondie dans le navigateur avant tout envoi.
- [ ] Polices et ressources servies par le site, pour ne pas transmettre l'adresse IP des visiteurs à un tiers.
- [ ] Mesure d'audience anonyme et refusable.
- [ ] Pages mentions légales, confidentialité et conditions d'utilisation à jour.
- [ ] Consentement explicite avant toute collecte d'adresse e-mail.

## Accessibilité
- [ ] Contraste AA au minimum sur tous les textes, y compris sur les photos et les dégradés.
- [ ] Zones de toucher d'au moins 44 px, appli utilisable à une main.
- [ ] Textes alternatifs sur les images, libellés sur les boutons-icônes.
- [ ] Navigation au clavier possible et focus visible.
- [ ] Animations désactivées si le système demande moins de mouvement (prefers-reduced-motion).

## Honnêteté envers l'utilisateur
- [ ] Les limites sont affichées (fiabilité d'une prévision, données indicatives).
- [ ] Une page explique d'où viennent les données et comment les résultats sont calculés.
- [ ] Les sources et leurs licences sont citées.

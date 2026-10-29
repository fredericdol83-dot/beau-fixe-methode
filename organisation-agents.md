# Organisation des agents IA

Une application web demande bien plus que du code. Pour couvrir tout le cycle de vie sans perdre le fil, le travail est réparti entre plusieurs agents, chacun dans son propre fil de discussion, avec un rôle clair. Les agents proposent, codent et testent. Les décisions restent humaines.

## Les rôles

- Coordinateur. Il reçoit les demandes, les découpe, ouvre un fil par sujet et suit l'avancement. Il ne code pas lui-même.
- Fils spécialisés, un par sujet : cadrage, design et maquettes, développement, tests, revue et sécurité, RGPD et accessibilité, mise en ligne, SEO et GEO, mesure, communication.
- Mémoire partagée. Un dossier de notes courtes (une note par sujet) lu par tous les agents : préférences, décisions, contraintes. Ce qu'un nouveau fil devrait sinon redemander y est écrit.
- Fichiers du projet. BRIEF.md, CLAUDE.md et JOURNAL.md font foi. Un agent les lit avant d'agir.

## Le cycle

1. Cadrage : brief, challenge en quatre rôles, périmètre du MVP.
2. Design et maquettes : plusieurs directions visuelles, choix humain.
3. Développement : par incréments courts et testables, sur une branche de travail.
4. Tests : automatiques sur de vraies réponses d'API, puis à la main sur un vrai téléphone.
5. Revue et sécurité : relecture du code, clés hors du code, dépendances.
6. RGPD et accessibilité : données minimales, mentions à jour, contraste AA.
7. Mise en ligne : aperçu d'abord, production ensuite.
8. SEO et GEO : pages utiles, données structurées, llms.txt.
9. Mesure : audience sans cookie, retours d'usage.
10. Communication : posts, visuels, vidéo, toujours relus.

## Trois validations humaines

- La maquette, avant le code. Aucun écran n'est développé sans maquette validée.
- L'aperçu, testé sur mobile. Chaque version est vérifiée sur une adresse d'aperçu avant d'aller plus loin.
- Le feu vert pour la production. Rien n'est mis en ligne sans accord explicite.

## Ce qui rend l'ensemble fiable

- Une tâche par fil, pour garder un contexte court et ciblé.
- Les corrections techniques se font sans déranger le décideur. Les choix produit et UX lui reviennent, avec une recommandation.
- Toute erreur corrigée devient une ligne dans les leçons apprises du CLAUDE.md.
- Aucune action irréversible (production, envoi public, suppression) sans accord.

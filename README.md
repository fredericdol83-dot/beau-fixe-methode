# Beau Fixe, la méthode

Retour d'expérience et ressources réutilisables issus de la création de [Beau Fixe](https://beau-fixe.app), une application web qui révèle où il fera beau ce week-end (ou frais en pleine canicule), à quelques heures porte à porte, en TGV, TER, voiture ou avion.

L'application a été conçue, développée et mise en ligne en dix jours avec une équipe d'agents IA, en vibe coding, sous ma direction. C'est une démarche personnelle, menée pour expérimenter, apprendre et partager. Ce dépôt ne contient pas son code. Il documente la méthode qui l'a rendue possible, pour que chacun puisse la reprendre sur ses propres projets.

## Les concepts mis en pratique

| Concept | Ce que j'en ai fait | Où le trouver |
|---|---|---|
| Ingénierie du contexte | Trois fichiers lus par chaque agent avant d'agir : l'intention, les règles, les décisions | [`modeles/`](modeles/) |
| Skills | Une compétence réutilisable qui cadre une idée, la challenge en quatre rôles et mène au MVP | [`skills/nouvelle-idee/`](skills/nouvelle-idee/) |
| Orchestration d'agents | Un coordinateur, un fil spécialisé par sujet, une mémoire partagée | [`organisation-agents.md`](organisation-agents.md) |
| Humain dans la boucle | Trois validations humaines : la maquette, l'aperçu sur mobile, la production | [`organisation-agents.md`](organisation-agents.md) |
| Connecteurs MCP | Un serveur MCP comme premier prototype, puis des connecteurs vers l'hébergement et les outils de publication | [`architecture.md`](architecture.md) |
| Frugalité | Contexte court, outils sobres, calculs préparés à l'avance | [`frugalite.md`](frugalite.md) |
| SEO et GEO | Être trouvé par les moteurs et cité par les IA génératives | [`checklists/seo-geo.md`](checklists/seo-geo.md) |
| Conformité dès la conception | Sécurité, RGPD et accessibilité vérifiés avant chaque mise en ligne | [`checklists/mise-en-ligne.md`](checklists/mise-en-ligne.md) |
| Données ouvertes | Des sources publiques et des API gratuites croisées pour créer un service nouveau | [`donnees-ouvertes.md`](donnees-ouvertes.md) |

## Structure du dépôt

```
.
├── modeles/                 BRIEF, CLAUDE.md et JOURNAL commentés
├── skills/nouvelle-idee/    skill de cadrage, du « j'ai une idée » au MVP
├── checklists/              mise en ligne, SEO et GEO, modèle de llms.txt
├── organisation-agents.md   rôles, cycle de vie, validations humaines
├── architecture.md          architecture de Beau Fixe, vue d'ensemble
├── frugalite.md             règles pour économiser les tokens
└── donnees-ouvertes.md      sources publiques mobilisées
```

## Démarrer

1. Copiez `modeles/` dans un nouveau dossier de projet et remplissez le BRIEF avant tout.
2. Installez la skill `nouvelle-idee` (voir son [README](skills/nouvelle-idee/README.md)) et dites « j'ai une idée ».
3. Mettez à jour CLAUDE.md et JOURNAL.md à chaque décision et à chaque erreur corrigée.
4. Passez les check-lists avant chaque mise en ligne.

## Contribuer

Les retours d'expérience sont les bienvenus. Voir [CONTRIBUTING.md](CONTRIBUTING.md).

## Licence

Textes et modèles sous licence [Creative Commons BY 4.0](LICENSE). Vous pouvez les réutiliser et les adapter, y compris pour un usage commercial, en citant la source.

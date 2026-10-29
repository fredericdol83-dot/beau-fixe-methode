# Beau Fixe, la méthode

Ressources ouvertes tirées de la création de [Beau Fixe](https://beau-fixe.app), une application web gratuite qui trouve où il fera beau (ou frais en pleine canicule) le week-end, à quelques heures porte à porte de chez soi, en TGV, TER, voiture ou avion.

L'application a été construite avec l'IA, en vibe coding, par quelqu'un qui n'est pas développeur de métier. Ce dépôt ne contient pas le code de l'application. Il rassemble ce qui a rendu le travail possible et reproductible, pour que d'autres puissent le réutiliser sur leurs propres projets.

## Ce qu'on y trouve

- `modeles/` : les trois fichiers de contexte à écrire avant la première ligne de code (BRIEF, CLAUDE.md, JOURNAL), commentés.
- `skills/nouvelle-idee/` : une skill pour Claude qui cadre une idée, la challenge en quatre rôles et mène à un MVP testable.
- `organisation-agents.md` : comment une petite équipe d'agents IA couvre tout le cycle de vie, avec un coordinateur, des fils spécialisés, une mémoire partagée et trois portes de validation humaine.
- `checklists/mise-en-ligne.md` : sécurité, RGPD et accessibilité avant d'ouvrir au public.
- `checklists/seo-geo.md` et `checklists/llms.txt` : être trouvé par les moteurs et cité par les IA génératives.
- `frugalite.md` : les règles pour dépenser moins de tokens et obtenir de meilleures réponses.
- `donnees-ouvertes.md` : les données publiques et API gratuites utilisées, avec nos remerciements.

## Comment s'en servir

1. Copiez `modeles/` dans un nouveau dossier de projet et remplissez le BRIEF avant tout.
2. Installez la skill `nouvelle-idee` dans Claude (dossier de skills) et dites simplement « j'ai une idée ».
3. Gardez CLAUDE.md et JOURNAL.md à jour à chaque décision et à chaque erreur corrigée.
4. Passez les check-lists avant chaque mise en ligne.

Tout est à adapter. Explorez, modifiez, et ouvrez une issue pour dire ce qui vous a servi ou ce qui manque.

## Licence

Textes et modèles sous licence [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.fr). Vous pouvez les réutiliser et les modifier, y compris pour un usage commercial, en citant la source.

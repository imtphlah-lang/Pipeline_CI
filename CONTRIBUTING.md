# Guide de contribution

Merci de contribuer au projet **Pipeline_CI** 🎉

## Workflow Git
- Les contributions se font via des **branches de fonctionnalité** (`feature/...`).
- Les branches doivent être fusionnées dans `develop` via **Pull Request**.
- La branche `main` est protégée et ne reçoit que du code validé.

## Convention de commits
Nous utilisons [Conventional Commits](https://www.conventionalcommits.org/).
Format : `<type>(scope): <description>`

Types autorisés :
- feat, fix, docs, style, refactor, test, chore

Exemples :
- `feat(api): ajout d’un endpoint`
- `fix(ci): correction du script de pipeline`

## Pull Requests
- Chaque PR doit être approuvée par au moins un membre.
- Les tests et la CI doivent passer avant la fusion.
- Les discussions doivent être résolues avant merge.

## Bonnes pratiques
- Documenter les nouvelles fonctionnalités.
- Ajouter des tests si nécessaire.
- Respecter la structure du projet.

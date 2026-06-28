# DevSetup — Mon Environnement Dev

Bienvenue sur mon repo de configuration dev. Ici je centralise ma config, mes notes et les bases pour démarrer un projet Node.js rapidement.

## Prérequis

- **Git** 2.x — [télécharger](https://git-scm.com/)
- **Node.js** 18+ — [télécharger](https://nodejs.org/)
- **VSCode** — [télécharger](https://code.visualstudio.com/)

## Installation

```bash
git clone https://github.com/babacleven/DevSetup.git
cd DevSetup
npm install
npm start
```

## Structure

```
DevSetup/
├── README.md
├── index.js
├── package.json
├── .gitignore
├── .editorconfig
└── notes/
    ├── git-basics.md
    ├── terminal.md
    └── vscode-setup.md
```

## Scripts

| Commande      | Description                        |
|---------------|------------------------------------|
| `npm start`   | Lance l'application                |
| `npm run dev` | Mode dev avec rechargement auto    |
| `npm test`    | Tests (à venir)                    |

## Notes personnelles

Tout ce que j'apprends sur les outils est dans le dossier `notes/`. Chaque semaine j'ajoute mes découvertes.

## Liens utiles

- [Git Cheatsheet](https://training.github.com/downloads/fr/github-git-cheat-sheet/)
- [Node.js docs](https://nodejs.org/docs/latest/api/)
- [VSCode docs](https://code.visualstudio.com/docs)

# DevSetup

## Presentation

DevSetup est un projet personnel realise dans le cadre de la **Phase 1 - Environnement & Setup** du parcours **Developpeur Full Stack** a **AKIENI Academy**.

Ce depot documente la mise en place de mon environnement de developpement. Il rassemble les outils installes, les commandes essentielles de Git et du terminal, ainsi que la configuration de VS Code.

L'objectif est de disposer d'une base solide et reproductible pour demarrer tout nouveau projet JavaScript / Node.js.

## Objectifs

- Configurer un environnement de developpement fonctionnel et reproductible.
- Maitriser les commandes essentielles de Git pour le versionnement.
- Comprendre les bases du terminal pour naviguer et manipuler les fichiers.
- Organiser des notes techniques dans une structure claire.
- Decouvrir Nodemon pour le developpement avec rechargement automatique.

## Pourquoi ces outils ?

Chaque outil a ete choisi pour son role precis dans le workflow de developpement :

- **Visual Studio Code** : editeur de code leger et extensible. Il offre un terminal integre, un debogueur et un vaste ecosysteme d'extensions (ESLint, Prettier, GitLens).
- **Git** : systeme de gestion de versions. Indispensable pour suivre l'evolution du code, collaborer et revenir a une version anterieure si necessaire.
- **GitHub** : plateforme de stockage et de collaboration. Elle heberge le depot Git et permet le travail en equipe via les pull requests et les issues.
- **Node.js** : environnement d'execution JavaScript cote serveur. Necessaire pour utiliser npm et executer du code JS hors du navigateur.
- **Nodemon** : outil de surveillance qui relance automatiquement l'application a chaque modification. Gain de temps considerable en developpement.

## Installation

Pour reproduire cet environnement sur une autre machine :

1. Installer Git depuis [git-scm.com](https://git-scm.com/).
2. Installer Node.js (version 18 ou superieure recommandee) depuis [nodejs.org](https://nodejs.org/).
3. Installer VS Code depuis [code.visualstudio.com](https://code.visualstudio.com/).
4. Verifier que Node.js est correctement installe :

```bash
node --version
npm --version
```

Les commandes doivent afficher des numeros de version. Pour Node, attendez-vous a `v18.x.x` ou `v20.x.x`.

5. Cloner le depot et installer les dependances :

```bash
git clone https://github.com/babacleven/DevSetup.git
cd DevSetup
npm install
```

## Commandes Git utilisees

Ces commandes representent le workflow Git de base, utilise tout au long du projet :

```bash
git init          # Initialiser un nouveau depot Git
git status        # Verifier l'etat des fichiers (modifies, ajoutes, supprimes)
git add .         # Ajouter tous les fichiers modifies a la zone de staging
git commit -m ""  # Enregistrer les modifications avec un message descriptif
git push          # Envoyer les commits locaux vers GitHub
git pull          # Recuperer les dernieres modifications depuis GitHub
```

## Structure du projet

```
DevSetup/
├── README.md           # Documentation principale du projet
├── index.js            # Point d'entree de l'application
├── package.json        # Dependances et scripts du projet
├── .gitignore          # Fichiers ignores par Git
├── .editorconfig       # Regles d'edition consistentes
└── notes/              # Notes techniques
    ├── git.md          # Commandes Git detaillees
    ├── terminal.md     # Commandes du terminal
    └── vscode.md       # Configuration VS Code
```

## Scripts disponibles

```bash
npm run dev    # Lance l'application avec Nodemon (rechargement automatique)
npm start      # Lance l'application avec Node
```

## A propos

Ce depot est amenage a evoluer au fil de la formation. Chaque nouvelle notion sera documentee ici pour servir de reference personnelle.

## Ressources

- [Documentation Node.js](https://nodejs.org/docs/latest/api/)
- [Guide GitHub - Premiers pas](https://docs.github.com/fr/get-started)
- [npm - Documentation officielle](https://docs.npmjs.com/)
- [Markdown Guide](https://www.markdownguide.org/)

---

**Auteur :** Aristote Cleven BABA\
Developpeur Full Stack en formation - Cohorte 2 AKIENI Academy

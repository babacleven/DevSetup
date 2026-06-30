# Git - Commandes principales

Git est un système de gestion de versions qui permet de suivre l'évolution d'un projet et de collaborer efficacement.

---

## git init

**Rôle :** Initialiser un nouveau dépôt Git dans un dossier.

```bash
git init
```

Après cette commande, un dossier caché `.git` est créé. Le projet est maintenant suivi par Git.

---

## git status

**Rôle :** Afficher l'état actuel du dépôt (fichiers modifiés, ajoutés, supprimés).

```bash
git status
```

Permet de savoir quels fichiers sont prêts à être commités et lesquels ne le sont pas encore.

---

## git add

**Rôle :** Ajouter des fichiers à la zone de staging (préparation avant le commit).

```bash
git add index.html
git add .
```

- `git add index.html` : ajoute un fichier spécifique.
- `git add .` : ajoute tous les fichiers modifiés.

---

## git commit

**Rôle :** Enregistrer les changements dans l'historique du dépôt.

```bash
git commit -m "Ajout de la page d'accueil"
```

Chaque commit est une sauvegarde avec un message qui décrit les changements effectués.

---

## git push

**Rôle :** Envoyer les commits locaux vers un dépôt distant (GitHub).

```bash
git push origin main
```

Permet de synchroniser le travail local avec le dépôt en ligne.

---

## git pull

**Rôle :** Récupérer les dernières modifications depuis le dépôt distant.

```bash
git pull origin main
```

Met à jour le dépôt local avec les changements effectués par d'autres contributeurs.

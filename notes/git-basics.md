# Git — Commandes essentielles

## Première config

```bash
git config --global user.name "babacleven"
git config --global user.email "babaaristote6@gmail.com"
```

## Workflow quotidien

```bash
git status              # voir ce qui a changé
git add .               # tout préparer
git commit -m "message" # sauvegarder
git push                # envoyer sur GitHub
git pull                # récupérer les mises à jour
```

## Branches

```bash
git branch <nom>        # créer une branche
git checkout <nom>      # changer de branche
git merge <nom>         # fusionner
git branch -d <nom>     # supprimer une branche
```

## Astuce

Toujours faire `git status` avant un commit pour vérifier ce qu'on envoie.

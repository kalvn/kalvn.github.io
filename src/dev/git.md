# Git

Je ne présente plus Git. C'est un outil impressionant mais également assez difficile à apréhender, notamment au niveau des commandes dont le nom n'est pas toujours logique.

Voici donc une cheat sheet  comme je les aime pour vous aider à vous y retrouver. Elle est principalement destinée à m'aider moi-même, c'est pourquoi elle peut sembler incomplète. Vous trouverez sur le web [des équivalents bien plus complets](https://www.cloudways.com/blog/git-cheat-sheet/).

## Supprimer un fichier du repository mais le garder en local
```bash
git rm --cached file1.txt
git commit -m "Removes unnecessary file."
git push origin master
```

## Modifier l'auteur d'un commit
```bash
git commit --amend --author="Author Name <email@address.com>"
```

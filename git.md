# Commandes Git  

## Configuration de Git  
  
git config --global user.name "username"  
git config --global user.email "email"  
git congif --list  : pour voir la configuration


## Commandes courantes

git init : initialisation du dépot  
git status : voir les modifications  
git add fichier : ajoute un fichier en transit  
git add . : ajoute tous les fichiers modifiés  
git commit -m "commentaire" : pour commit  
git commit -a -m "commentaire" pour commit un fichier deja existant   sans passer par git add  
git log / git log --oneline : affiche la liste des commits
  
Pour rajouter un fichier oublié dans un commit :  
git add fichier-oublié
git commit --amend  

## Branches
git branch : pour la branch ou l'on est  
git branch nom-branche : pour créer une branche
git switch nom-branche : pour changer de branche
git switch -c nom-branche : pour créer une branche et switcher dessus (c pour create)  

### Fusion de branche
Se mettre sur le main  
git merge non-de-la-branche (à fusionner)

### Suppression de branche
A partir d'une autre branche  
git branch -d nom-branche

### Renommer une branche
Sur la branche à renommer
git branch -m nouveau-nom

## Commit
git checkout id-du-commit : revenir sur un commit  
git tag nom-du-tag : pour donner un tag à un commit, se postionner sur le commit  

## Push
git remote add origin https://github.com/UTurtleDev/nom-du-depot.git pour lier le dépôt  
git push -u origin main : Mettre à jour sur git  
git remote -v : pour vérifier si le dépôt est lié




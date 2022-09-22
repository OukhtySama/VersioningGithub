# VersioningGithub

# Les fichiers ont trois états dans git :
- Modifié (modified) checker avec la commande "git status"
- Indexé (staged) utiliser la commande "git add"
- Validé (commited) utiliser la commande "git commit" on va indéxer toutes les mis à jours

-m est pour ajouter un msg de commit après le -m "ajouter msg"
- push

# Création et indexage 
- git add .
- git commit -m "update"
- git push -u origin main
- sigit  la modification ne se fait pas il faut rajouter l'url "git remote add origin git@github.com:OukhtySama/VersioningGithub.git"

# Clonage 
- git clone https://github.com/OukhtySama/VersioningGithub.git

# Gestion fichier
- touch test.txt(nom fichier) : touch permet de créer un fichier 
- git add .
- git commit -m "Update" ( il faut commit le plus souvent possible  1 tache un commit)
- git rm --cached test.txt (nom fichier)
- git add .
- git status
- git reset HEAD test.txt : pointer le plus proche 
- git log : permet de lister tous les commit et de voir les ID
- git log --pretty=oneline :permet d'afficher le commit sur lequel on travail
- git mv <nom du fichier> <nouveau nom du fichier>

# Branche 
- git branch -d <nom de la branch> : permet de supprimer la branche 
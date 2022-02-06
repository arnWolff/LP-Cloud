# Git

Git est un logiciel de gestion de versions décentralisé. C'est un logiciel libre créé par Linus Torvalds, auteur du noyau Linux, et distribué selon les termes de la licence publique générale GNU version 2. Le principal contributeur actuel de git et depuis plus de 16 ans est Junio C Hamano. En 2016, il s’agit du logiciel de gestion de versions le plus populaire qui est utilisé par plus de douze millions de personnes

## Quelques commandes

Git dispose notamment des commandes suivantes :

* `git init​` - crée un nouveau dépôt ;
* `git clone` -​ clone un dépôt distant ;
* `git add​` - ajoute de nouveaux objets blobs dans la base des objets pour chaque fichier modifié depuis le dernier commit. Les objets précédents restent inchangés ;
* `git commit​` - intègre la somme de contrôle SHA-1 d'un objet tree et les sommes de contrôle des objets commits parents pour créer un nouvel objet commit ;
* `git branch​` - liste les branches ;
* `git merge​` - fusionne une branche dans une autre ;
* `git rebase​` - déplace les commits de la branche courante devant les nouveaux commits d’une autre branche ;
* `git log​` - affiche la liste des commits effectués sur une branche ;
* `git push​` - publie les nouvelles révisions sur le remote. (La commande prend différents paramètres) ;
* `git pull​` - récupère les dernières modifications distantes du projet (depuis le Remote) et les fusionne dans la branche courante ;
* `git stash` -​ stocke de côté un état non commité afin d’effectuer d’autres tâches ;
* `git checkout` -​ annule les modifications effectuées, déplacement sur une référence (branche, hash) ;
* `git switch` -​ changement de branche ;
* `git remote` -​ gestion des remotes.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

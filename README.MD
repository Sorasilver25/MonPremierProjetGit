<!--    
Partie 1 : Les bases de Git
        1. Initialisation d'un répertoire
            Git init -> permet d'initier un dépot git en local 
            Git add -> ca permet de stage des changements
            Git commit permet de sauvegarder les fichiers qu'on a git add en local
            Les commit permettent d'avoir une tracabilité des changements effectués sur les branches
        
        2. Historique et modifications
            Git add . permet d'ajouter le main.c dans les fichiers a envoyer dans le commit (on peut aussi cliquer sur le + avec l'UI de Vs code)
            Git log -> Les logs représentent les commits suivi de l'auteur et de la date des commits
            Git diff permet de voir les nouveaux changements effectués par rapport a l'anciene version de fichier

        3. Utilisation de git ignore
            ajout du fichier .gitignore

Partie 2 : Utilisation de GitHub
        1. Création d'un dépôt GitHub
            Un depot public est visible et on peut choisir qui peut commit des fichiers
            Un depot privé n'est visible que par nous.
        2. Lier le dépôt local à GitHub
            git remote add origin sert a lier le depot local au depot en ligne present sur git hub
            git push -u permet d'associer sa branche local a une branche distante pour que les prochain push et pull on est plus besoin de specifier le nom des branches

Partie 3 : Collaboration et Workflows
        1. Créer et gérer des branches
            Creer des branches permet de decouper des taches en plusieurs sous taches et aussi une tracabilité des fonctionnalités ajoutés
            De plus, en cas d'abandon d'une fonctionnalité dans le projet, on peut simplement supprimer la branche.

            Git branch permet de lister toute les branches.
        2. Pull Requests (PR)

Partie 4 : Workflow GitHub Flow vs Git Flow
        1. GitHub Flow
        GitHub flow est utilisé dans le cadre de projet simple n'ayant qu'une seule branche principale, git flow lui est utilisé pour des projets plus complexes car en plus des features il prend en compte les bugs, les release, les features, etc.
        -->
        
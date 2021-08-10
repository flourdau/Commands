##  GIT :
***Global :*** 

    git config --global user.name

    git config --global user.name "USERNAME"
    git config --global user.email "EMAIL"
    git config --global color.ui auto
___
***Local :***

    git config --local user.name
    git config --local user.email
___
___
`git init [nom-du-projet]`  
***Crée un dépôt local à partir du nom spécifié***  
___
`git clone [url]`  
***Télécharge un projet et tout son historique de versions***  
___
`git status`  
***Liste tous les nouveaux fichiers et les fichiers modifiés à commiter***  
___
`git add [fichier]`  
***Ajoute un instantané du fichier, en préparation pour le suivi de version***  
___
`git reset [fichier]`  
***Enleve le fichier de l'index, mais conserve son contenu***  
___
`git diff`  
***Montre les modifications de fichier qui ne sont pas encore indexées***  
___
`git diff --staged`  
***Montre les différences de fichier entre la version indexée et la dernière version***  
___
`git commit -m "[message descriptif]"`  
***Enregistre des instantanés de fichiers de façon permanente dans l'historique des versions***  
___
`git branch`  
***Liste toutes les branches locales dans le dépôt courant***  
___
`git branch [nom-de-branche]`  
***Crée une nouvelle branche***  
___
`git checkout [nom-de-branche]`  
***Bascule sur la branche spécifiée et met à jour le répertoire de travail***  
___
`git merge [nom-de-branche]`  
***Combine dans la branche courante l'historique de la branche spécifiée***  
___
`git branch -d [nom-de-branche]`  
***Supprime la branche spécifié***  
___
`git rm [fichier]`  
***Supprime le fichier du répertoire de travail et met à jour l'index***  
___
`git mv [fichier-nom] [fichier-nouveau-nom]`  
***Renomme le fichier et prépare le changement pour un commit***  
___
`git ls-files --other --ignored --exclude-standard`  
***Liste tous les fichiers exclus du suivi de version dans ce projet***  
***Un fichier texte nommé .gitignore permet d'éviter le suivi de version accidentel pour les fichiers et chemins***   ***correspondant aux patterns spécifiés***  
___
`git stash`  
***Enregistre de manière temporaire tous les fichiers sous suivi de version qui ont été modifiés ("remiser son travail")*** 
___
`git stash list`  
***Liste toutes les remises***  
___
`git stash pop`  
***Applique une remise et la supprime immédiatement***  
___
`git stash drop`  
***Supprime la remise la plus récente***  
___
`git log`  
***Montre l'historique des versions pour la branche courante***  
___
`git log --follow [fichier]`  
***Montre l'historique des versions, y compris les actions de renommage, pour le fichier spécifié***  
___
`git diff [premiere-branche]...[deuxieme-branche]`  
***Montre les différences de contenu entre deux branches***  
___
`git show [commit]`  
***Montre les modifications de métadonnées et de contenu inclues dans EXCLURE DU SUIVI DE VERSION le commit spécifié***  
___
`git reset [commit]`  
***Annule tous les commits après `[commit]`, en conservant les modifications localement***  
___
`git reset --hard [commit]`  
***Supprime tout l'historique et les modifications effectuées après le commit spécifié***  
___
`git fetch [nom-de-depot]`  
***Récupère tout l'historique du dépôt nommé***  
___
`git merge [nom-de-depot]/[branche]`  
***Fusionne la branche du dépôt dans la branche locale courante***  
___
`git push [alias] [branche]`  
***Envoie tous les commits de la branche locale vers GitHub***  
___
`git pull`  
***Récupère tout l'historique du dépôt nommé et incorpore les modifications***  
___

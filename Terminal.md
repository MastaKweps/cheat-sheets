 *Commande à retenir pour le terminal* 

**_Commande de base_**

| Commande  | Description | Exemple |
|-----------|------------|---------|
| `pwd`     | Affiche le répertoire courant | `pwd` |
| `ls`      | Liste les fichiers et dossiers | `ls -l` (détails) |
| `cd`      | Change de répertoire | `cd /home/user` |
| `mkdir`   | Crée un dossier | `mkdir mon_dossier` |
| `rmdir`   | Supprime un dossier vide | `rmdir mon_dossier` |
| `rm`      | Supprime un fichier ou un dossier | `rm -rf mon_dossier` |
| `cp`      | Copie un fichier ou un dossier | `cp fichier.txt /destination/` |
| `mv`      | Déplace ou renomme un fichier/dossier | `mv fichier.txt nouveau_nom.txt` |


**_Gestion des fichiers et dossiers_**

| Commande  | Description | Exemple |
|-----------|------------|---------|
| `touch`   | Crée un fichier vide | `touch nouveau_fichier.txt` |
| `find`    | Recherche un fichier dans un répertoire | `find /home -name "*.txt"` |
| `locate`  | Trouve rapidement un fichier | `locate fichier.txt` |
| `stat`    | Affiche les informations d'un fichier | `stat sichier.txt` |
| `du`      | Affiche l’espace utilisé par un fichier/dossier | `du -sh fichier.txt` |
| `df`      | Affiche l’espace disque utilisé | `df -h` |


**_Manipulation de texte_**

| Commande  | Description | Exemple |
|-----------|------------|---------|
| `cat`     | Affiche le contenu d'un fichier | `cat fichier.txt` |
| `tac`     | Affiche un fichier à l’envers | `tac fichier.txt` |
| `less`    | Ouvre un fichier page par page | `less fichier.txt` |
| `head`    | Affiche les 10 premières lignes | `head -20 fichier.txt` |
| `tail`    | Affiche les 10 dernières lignes | `tail -20 fichier.txt` |


**_Commande Git_**

| Commande                | Description | Exemple |
|-------------------------|------------|---------|
| `git init`             | Initialise un nouveau dépôt Git | `git init mon-projet` |
| `git clone`            | Clone un dépôt distant | `git clone https://github.com/user/repo.git` |
| `git status`           | Affiche l’état du dépôt | `git status` |
| `git add`              | Ajoute des fichiers à l'index | `git add fichier.txt` |
| `git commit -m "msg"`  | Enregistre les modifications avec un message | `git commit -m "Ajout du fichier"` |
| `git log`              | Affiche l'historique des commits | `git log --oneline` |
| `git diff`             | Montre les différences entre versions | `git diff fichier.txt` |
| `git branch`           | Liste ou crée des branches | `git branch nouvelle-branche` |
| `git checkout`         | Change de branche | `git checkout main` |
| `git merge`            | Fusionne une branche | `git merge nouvelle-branche` |
| `git pull`             | Récupère les modifications distantes | `git pull origin main` |
| `git push`             | Envoie les commits vers le dépôt distant | `git push origin main` |
| `git reset --hard`     | Réinitialise le dépôt à un état précédent | `git reset --hard HEAD~1` |
| `git stash`            | Met temporairement de côté des modifications | `git stash` |
| `git stash pop`        | Restaure les modifications mises de côté | `git stash pop` |
| `git rebase`           | Rejoue les commits d’une branche sur une autre | `git rebase main` |
| `git tag`              | Ajoute un tag sur un commit | `git tag v1.0.0` |
| `git remote -v`        | Liste les dépôts distants | `git remote -v` |
| `git fetch`            | Récupère les modifications sans les fusionner | `git fetch origin` |

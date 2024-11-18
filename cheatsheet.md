<!-- cmd terminal  -->

<!-- Action sur repository -->
git clone *url*                     <!-- Chope depuis github jusqu'a fichier locaux depuis un url -->
git init                            <!-- Nouveau repo attention dans quel fichier on est -->

<!-- Commandes de base -->

git status                          <!-- Affiche le status -->
git add *nom fichier*               <!-- Add changes to staging -->
    git add nomdurepertoire
    git add repertoire/nomdufichier
    git add .    (ajoute tous les fichiers à l’index)
    git add *.php  (ajoute tous les fichiers avec l’extension php à l’index)
git commit -m *Message*             <!-- Commit changes with a message -->
git log                             <!-- View commit history -->

<!-- Commande en raport avec les Branch -->
git branch                          <!-- List branches -->
git branch *branch-name*            <!-- Create a new branch -->
git checkout *branch-name*          <!-- Switch to a branch -->
git merge *branch-name*             <!-- Merge changes from a branch -->
git branch -d *branch-name*         <!-- Delete a branch -->


<!-- Intergir avec repo en ligne -->
git remote                          <!-- List remotes -->
git remote add *name* *url*         <!-- Add a remote -->
git push *remote* *branch*          <!-- Push changes to a remote -->
git pull *remote* *branch*          <!-- Pull changes from a remote -->


<!-- Ctrl+Z -->
git pull                            <!-- Fetch and merge changes -->
git fetch                           <!-- Fetch changes without merging -->
git reset --hard HEAD               <!-- Discard changes -->
git revert *commit-hash*            <!-- Revert changes in a commit -->








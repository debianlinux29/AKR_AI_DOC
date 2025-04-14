Git est un système de contrôle de version largement utilisé pour gérer le code source durant le développement de logiciels. 

### Qu'est-ce que Git ?

Git est un outil qui permet de suivre les modifications apportées à des fichiers, notamment le code source. Il permet de collaborer avec d'autres développeurs en gérant les versions des fichiers et en facilitant le partage et l’intégration du travail de chacun.

### Pourquoi utiliser Git ?

1. **Historique des versions** : Git garde une trace de chaque modification, ce qui permet de revenir à une version antérieure si nécessaire.
2. **Travail collaboratif** : Plusieurs développeurs peuvent travailler sur le même projet sans écraser les modifications des autres.
3. **Branchement et fusion** : Git permet de créer des "branches" pour travailler sur des fonctionnalités ou des correctifs sans affecter le code principal. Ensuite, ces branches peuvent être fusionnées.

### Concepts de base

1. **Dépôt (repository)** : Un dossier qui contient votre projet et l'historique des versions.
2. **Commit** : Une capture des modifications apportées à votre code. Chaque commit a un identifiant unique.
3. **Branch (branche)** : Une version du projet où vous pouvez effectuer des modifications sans affecter la branche principale (souvent appelée `main` ou `master`).
4. **Merge (fusion)** : L’action de combiner les modifications d'une branche dans une autre.

### Commandes Git de base

- **`git init`** : Initialise un nouveau dépôt Git.
- **`git clone [url]`** : Clone un dépôt distant sur votre machine locale.
- **`git status`** : Affiche le statut actuel du dépôt (fichiers modifiés, fichiers en attente, etc.).
- **`git add [fichier]`** : Ajoute un fichier à la zone de staging (prépare le fichier pour le commit).
- **`git commit -m "message"`** : Enregistre les changements ajoutés avec un message descriptif.
- **`git push`** : Envoie vos commits locaux vers un dépôt distant.
- **`git pull`** : Récupère et intègre les changements du dépôt distant dans votre dépôt local.
- **`git branch`** : Liste les branches locales.
- **`git checkout [branche]`** : Change de branche.
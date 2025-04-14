### 1. **Commit**
Un "commit" est une opération dans Git qui enregistre les modifications apportées à votre dépôt local. Lorsqu'un commit est effectué, Git prend un instantané de l'état actuel de votre projet et l'enregistre avec un message descriptif. Chaque commit possède un identifiant unique (un hash) qui permet de le référencer ultérieurement. Les commits permettent de suivre l'historique des modifications et de revenir à des versions antérieures si nécessaire.

**Exemple de commande :**
```bash
git commit -m "Description des changements"
```

### 2. **Branch**
Une "branch" (ou branche) est une ligne de développement dans un projet. Par défaut, le dépôt a une branche principale appelée `main` (ou `master` dans certaines configurations). Les branches permettent de travailler sur des fonctionnalités, des corrections de bogues ou d'autres modifications sans affecter la branche principale. Vous pouvez créer une nouvelle branche, y effectuer des commits, puis fusionner ces modifications avec d'autres branches lorsque vous êtes prêt.

**Exemple de commande pour créer une nouvelle branche :**
```bash
git branch nom_de_la_brache
```

**Pour basculer vers une autre branche :**
```bash
git checkout nom_de_la_brache
```

### 3. **Merge**
Le "merge" (fusion) est le processus qui consiste à combiner les modifications d'une branche dans une autre. Lorsque vous avez terminé des modifications sur une branche (par exemple, une branche de fonctionnalité), vous pouvez effectuer un merge pour intégrer ces changements dans une autre branche (souvent la branche principale). Cela permet de rassembler tout le travail effectué sur différentes branches.

**Exemple de commande pour fusionner une branche dans la branche actuelle :**
```bash
git merge nom_de_la_branche_a_fusionner
```

### Résumé
- **Commit** : Enregistrement des modifications dans le dépôt.
- **Branch** : Création de lignes parallèles de développement.
- **Merge** : Combinaison de modifications de différentes branches.

Ces concepts fondamentaux de Git sont essentiels pour gérer efficacement le développement d'un projet, faciliter la collaboration et maintenir un historique clair des modifications. N'hésitez pas à poser des questions pour approfondir certains points!
### Étape 1 : Installer Git et Python

Avant de commencer, assurez-vous d'avoir Git et Python installés sur votre machine. Vous pouvez vérifier cela en exécutant les commandes suivantes dans l'invite de commandes (CMD) :

```bash
git --version
python --version
```

Si ces commandes ne fonctionnent pas, téléchargez et installez :

- [Git](https://git-scm.com/download/win)
- [Python](https://www.python.org/downloads/windows/)

### Étape 2 : Cloner un dépôt Git (si ce n'est pas déjà fait)

Si vous n'avez pas encore cloné le dépôt, exécutez la commande suivante dans l'invite de commandes. Remplacez `URL_DU_DEPOT` par l'URL du dépôt que vous souhaitez cloner :

```bash
git clone URL_DU_DEPOT
```

Exemple :

```bash
git clone https://github.com/nom_utilisateur/nom_depot.git
```

### Étape 3 : Naviguer dans le répertoire du dépôt

Une fois le dépôt cloné, naviguez dans le répertoire du dépôt :

```bash
cd nom_depot
```

(Remplacez `nom_depot` par le nom du répertoire cloné.)

### Étape 4 : Créer un environnement virtuel

Pour créer un environnement virtuel, utilisez la commande suivante (en supposant que vous avez Python 3.x) :

```bash
python -m venv nom_env
```

Remplacez `nom_env` par le nom que vous souhaitez donner à votre environnement virtuel.

### Étape 5 : Activer l'environnement virtuel

Pour activer l'environnement virtuel, exécutez la commande suivante :

```bash
nom_env\Scripts\activate
```

Vous devriez voir le nom de votre environnement virtuel au début de la ligne de commande, indiquant qu'il est activé.

### Étape 6 : Installer les dépendances nécessaires

Enfin, installez les dépendances nécessaires à votre projet. Si un fichier `requirements.txt` est présent dans le répertoire du dépôt, vous pouvez exécuter :

```bash
pip install -r requirements.txt
```

### Étape 7 : Désactiver l'environnement virtuel (au besoin)

Pour désactiver l'environnement virtuel lorsque vous avez terminé, vous pouvez simplement taper :

```bash
deactivate
```

### Résumé

Voici un récapitulatif des commandes nécessaires :

1. Cloner le dépôt :
   ```bash
   git clone URL_DU_DEPOT
   ```

2. Naviguer dans le répertoire :
   ```bash
   cd nom_depot
   ```

3. Créer un environnement virtuel :
   ```bash
   python -m venv nom_env
   ```

4. Activer l'environnement virtuel :
   ```bash
   nom_env\Scripts\activate
   ```

5. Installer les dépendances :
   ```bash
   pip install -r requirements.txt
   ```

6. Désactiver l'environnement virtuel :
   ```bash
   deactivate
   ```

En suivant ces étapes, vous serez prêt à travailler avec votre projet Python dans un environnement virtuel.

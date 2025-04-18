Pour installer Python par défaut sur un système Windows 64 bits, suivez ces étapes :

### Étape 1 : Télécharger Python

1. **Visitez le site officiel de Python** :
   Allez sur [python.org](https://www.python.org/downloads/).

2. **Téléchargez la version pour Windows** :
   Cliquez sur le bouton "Download Python" qui correspond à la dernière version stable.

### Étape 2 : Installer Python

1. **Exécutez le fichier téléchargé** :
   Trouvez le fichier `.exe` que vous avez téléchargé (généralement dans le dossier "Téléchargements") et double-cliquez dessus pour lancer l'installation.

2. **Options d'installation** :
   - **Important** : Cochez la case `Add Python to PATH` en bas de la fenêtre de l'installateur. Cela rendra Python et `pip` (le gestionnaire de paquets Python) accessibles depuis l'invite de commande.
   - Cliquez sur "Install Now" pour une installation recommandée ou sur "Customize installation" si vous souhaitez modifier certaines options (comme choisir les packages supplémentaires).

3. **Attendez la fin de l'installation** :
   Laissez l'installation se terminer. Cela peut prendre quelques minutes.

4. **Vérification de l'installation** :
   Une fois l'installation terminée, ouvrez l'Invite de commandes (vous pouvez la trouver en cherchant "cmd" dans le menu Démarrer).

### Étape 3 : Vérifier l'installation

Dans l'invite de commandes, tapez :

```bash
python --version
```

ou

```bash
python -V
```

Vous devriez voir affichée la version de Python que vous avez installée.

Pour vérifier l'installation de `pip`, tapez :

```bash
pip --version
```

### Étape 4 : Mettre à jour pip (facultatif)

Il est souvent recommandé de mettre à jour `pip` après l'installation. Dans l'invite de commandes, exécutez :

```bash
python -m pip install --upgrade pip
```
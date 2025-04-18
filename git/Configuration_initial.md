Pour configurer votre nom et votre adresse email dans Git, vous pouvez utiliser les commandes suivantes dans votre terminal ou invite de commandes :

1. Ouvrez votre terminal.

2. Configurez votre nom utilisateur :

   ```bash
   git config --global user.name "Votre Nom"
   ```

3. Configurez votre adresse email :

   ```bash
   git config --global user.email "votre.email@example.com"
   ```

L'option `--global` signifie que ces paramètres s'appliqueront à tous les dépôts Git de votre machine. Si vous souhaitez configurer ces informations pour un dépôt spécifique uniquement, omettez l'option `--global` et exécutez les commandes à l'intérieur du répertoire de votre dépôt.

Pour vérifier que votre configuration a bien été enregistrée, vous pouvez utiliser :

```bash
git config --global --list
```

Cela affichera la configuration actuelle de Git, y compris votre nom et votre adresse email.

1. #### Installation python
    
    1.  Télécharger Python: Rendez-vous sur le site officiel [python](https://www.python.org/downloads/) et téléchargez la dernière version de Python.

    2. Installation: Suivez les instructions d'installation pour votre système d'exploitation (Windows, macOS, Linux).

    3. Vérification de l'Installation: Ouvrez un terminal ou une invite de commande et tapez:

    ```bash
    python --version
    # ou 
    python3 --version
    ```

2. ### Mode d'exécution
    1. #### mode interactive 
        python3 est une commande utilisée pour exécuter l'interpréteur Python
        Lorsque vous tapez python3 dans le terminal, vous entrez dans l'interpréteur interactif de Python 3, où vous pouvez exécuter des commandes Python ligne par ligne.
        ```
        (test_python) root@user:/home/user/workspace/test_python# python
        Python 3.12.3 (main, Jan 17 2025, 18:03:48) [GCC 13.3.0] on linux
        Type "help", "copyright", "credits" or "license" for more information.
        >>> exit()
        (test_python) root@user:/home/user/workspace/test_python# 
        ```

    2. #### Mode script 
        python3 script.py est une commande utilisée pour exécuter un fichier script Python nommé script.py, lorsque vous exécutez cette commande, l'interpréteur Python exécute le code contenu dans le fichier script.py
        1. Ouvrez un éditeur de texte (comme Notepad, VS Code).
        2. Copiez le code ci-dessous et enregistrez-le dans un fichier nommé script.py 
        ```python
        print("hello")
        ```
        3. lancer la commande: 
        ```bash
        python3 script.py
        ```
        ```
        (test_python) root@user:/home/user/workspace/test_python/src# python3 script.py 
        hello
        (test_python) root@user:/home/user/workspace/test_python/src# 
        ```

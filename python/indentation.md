L'indentation en Python est un aspect fondamental de la syntaxe du langage. Contrairement à d'autres langages de programmation qui utilisent des accolades {} ou des mots-clés pour délimiter les blocs de code, Python utilise l'indentation pour définir la structure du code.

L'indentation détermine la portée des blocs de code, comme ceux des boucles, des conditions, des fonctions, des classes, etc.

### 1. Règles d'Indentation

**Espaces ou Tabulations:** Vous pouvez utiliser des espaces ou des tabulations pour indenter votre code, mais il est recommandé de choisir l'un ou l'autre et de s'y tenir. La convention la plus courante est d'utiliser 4 espaces par niveau d'indentation.

**Consistance:** Soyez cohérent dans l'utilisation des espaces ou des tabulations. Ne mélangez pas les deux dans le même fichier.

**Indentation Obligatoire:** Toute instruction qui fait partie d'un bloc de code doit être indentée. Si vous omettez l'indentation, Python lèvera une erreur de syntaxe.

### 2. Exemples d'Indentation

Voici quelques exemples pour illustrer l'importance de l'indentation en Python:

**Exemple 1:** Conditionnelle

```python
x = 10

if x > 5:
    print("x est supérieur à 5")
    print("Ceci fait partie du bloc if")
print("Ceci est en dehors du bloc if")
```

Dans cet exemple, les deux premières instructions print sont indentées et font partie du bloc if, tandis que la dernière instruction print n'est pas indentée et est exécutée indépendamment de la condition.

**Exemple 2:** Boucle

```python
for i in range(5):
    print("Itération", i)
    if i % 2 == 0:
        print(i, "est un nombre pair")
print("Boucle terminée")
```

**Exemple 3:** Fonction

```python
def saluer(nom):
    print("Bonjour,", nom)
    print("Bienvenue!")

saluer("Alice")
```

### 3. Erreurs d'Indentation

Si l'indentation n'est pas correcte, Python lèvera une erreur de syntaxe. Par exemple:

```python
x = 10

if x > 5:
print("x est supérieur à 5")  # Erreur d'indentation
```

Cela produira une erreur comme:

```python
IndentationError: expected an indented block
```
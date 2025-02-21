## Variables 

En Python, une variable est un espace de stockage qui a un nom et qui peut contenir une valeur. Les variables sont utilisées pour stocker des données que vous pouvez utiliser et manipuler dans votre programme. Voici un aperçu des concepts clés liés aux variables en Python:

### 1. Déclaration des Variables
En Python, vous n'avez pas besoin de déclarer le type de la variable avant de l'utiliser. Vous pouvez simplement assigner une valeur à une variable en utilisant le signe égal (=)

exemples:

```python
# Déclaration de variables
nom = "test"  # Une chaîne de caractères (str)
age = 30       # Un entier (int)
taille = 1.75  # Un float (float)
est_etudiant = True  # Un booléen (bool)
```

### 2. Nommage des Variables

Les noms de variables doivent respecter certaines règles :

1. Ils peuvent contenir des lettres (a-z, A-Z), des chiffres (0-9) et des underscores (_).

2. Ils ne peuvent pas commencer par un chiffre.

3. Ils ne doivent pas contenir d'espaces ou de caractères spéciaux (comme @, #, $, etc.).

4. Les noms de variables sont sensibles à la casse, ce qui signifie que maVariable et mavariable  sont considérés comme deux variables différentes.

#### Exemples de Noms Valides :

```python
ma_variable = 10
age_utilisateur = 25
nom1 = "test"
```

#### Exemples de Noms Invalides :

```python
1er_nom = "Alice"  # Commence par un chiffre
ma-variable = 5     # Contient un tiret
```

### 3. Types de Variables

Les variables en Python peuvent contenir différents types de données, comme mentionné précédemment (int, float, str, list, dict, etc.). Le type de la variable est déterminé par la valeur qui lui est assignée.

#### Exemple :

```python
x = 5          # x est un int
y = 3.14       # y est un float
z = "Bonjour"  # z est une str
```

### 4. Modification des Variables

Vous pouvez modifier la valeur d'une variable à tout moment en lui assignant une nouvelle valeur.

#### Exemple :

```python
age = 30
print(age)  # Affiche 30

age = 31    # Modification de la valeur
print(age)  # Affiche 31
```

### 5. Utilisation des Variables

Les variables peuvent être utilisées dans des expressions, des fonctions, des boucles, etc.

#### Exemple :

```python
a = 10
b = 5
somme = a + b  # Utilisation des variables dans une expression
print("La somme est:", somme)  # Affiche "La somme est: 15"
```

### 6. Variables Globales et Locales

```python
x = 10  # Variable globale

def ma_fonction():
    y = 5  # Variable locale
    print("Dans la fonction, x =", x)  # Peut accéder à x
    print("Dans la fonction, y =", y)  # Peut accéder à y

ma_fonction()
# print(y)  # Cela provoquerait une erreur, car y n'est pas accessible ici
```
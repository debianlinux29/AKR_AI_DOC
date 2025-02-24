En Python, les types de données sont des classifications qui définissent le type de valeur qu'une variable peut contenir.

### 1. Types de Données Numériques

1. **int** : Représente des entiers (nombres sans décimales).

```python
a = 10
b = -5
```

2. **float** : Représente des nombres à virgule flottante (nombres avec décimales).

```python
c = 3.14
d = -0.001
```

3. **complex** : Représente des nombres complexes, qui ont une partie réelle et une partie imaginaire.

```python
e = 2 + 3j  # 2 est la partie réelle, 3j est la partie imaginaire
```

### 2. Types de Données Séquentiels

1. **str** : Représente une chaîne de caractères (texte).

```python
nom = "Alice"
message = 'Bonjour, monde!'
```

2. **list** : Représente une liste ordonnée et modifiable d'éléments. Les éléments peuvent être de types différents.

```python
fruits = ["pomme", "banane", "cerise"]
```

3. **tuple** : Représente une séquence ordonnée d'éléments, mais immuable (non modifiable).

```python
coordonnees = (10.0, 20.0)
```

4. **range** : Représente une séquence d'entiers, souvent utilisée dans les boucles.

```python
nombres = range(1, 10)  # de 1 à 9
```

### 3. Types de Données Associatifs

1. **dict** : Représente un dictionnaire, qui est une collection non ordonnée de paires clé-valeur. 

```python
personne = {
    "nom": "Alice",
    "age": 30,
}
```

### 4. Types de Données Booléens

1. **bool** : Représente une valeur de vérité, qui peut être soit True ou False

```python
vrai = True
faux = False
```

### 5. Types de Données Spéciaux

1. **NoneType** : Représente une valeur nulle ou absente. Il est représenté par le mot-clé 

```python
resultat = None
```

### 6. Conversion de Types

Python permet de convertir entre différents types de données à l'aide de fonctions intégrées:

```python
int() # Convertit en entier.
float() # Convertit en nombre à virgule flottante.
str() # Convertit en chaîne de caractères.
list() # Convertit en liste.
tuple() # Convertit en tuple.
dict() # Convertit en dictionnaire.
```

**Exemples de Conversion:**

```python
# Conversion d'un float en int
x = 3.14
y = int(x)  # y vaudra 3

# Conversion d'un int en str
z = str(y)  # z vaudra "3"

# Conversion d'une chaîne en liste
chaine = "Bonjour"
liste = list(chaine)  # liste vaudra ['B', 'o', 'n', 'j', 'o', 'u', 'r']
```
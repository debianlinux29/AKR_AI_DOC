Le type int en Python représente des nombres entiers, c'est-à-dire des nombres sans partie décimale.

### 1. Caractéristiques du Type 

1. **Valeurs Entières**: Les valeurs de type int peuvent être positives, négatives ou nulles.

2. **Pas de Limite Précise**: En Python, les entiers peuvent être de n'importe quelle taille, limités uniquement par la mémoire disponible. Cela signifie que vous pouvez travailler avec des entiers très grands sans vous soucier de débordements, contrairement à certains autres langages de programmation.

3. **Représentation**: Les entiers peuvent être représentés en décimal, en binaire, en octal ou en hexadécimal.

    ```python
    42 # Décimal
    0b101010 # Binaire (qui est 42 en décimal)
    0o52 # Octal (qui est 42 en décimal)
    0x2A # Hexadécimal (qui est 42 en décimal)
    ```

### 2. Opérations sur les Entiers

```python 
+ # Addition
- # Soustraction 
* # Multiplication 
/ # Division 
// # Division entière
% # Reste de la division
** # Exponentiation 
```

**Exemples d'Opérations:**

```python
# Déclaration de variables
a = 10
b = 3

# Addition
somme = a + b  # 13

# Soustraction
difference = a - b  # 7

# Multiplication
produit = a * b  # 30

# Division
division = a / b  # 3.3333...
division_entière = a // b  # 3 (division entière)

# Modulo
reste = a % b  # 1

# Exponentiation
puissance = a ** b  # 1000 (10 à la puissance 3)
```

Vous pouvez convertir d'autres types de données en int à l'aide de la fonction int()

**exemple:**

```python
# Conversion d'une chaîne en entier
chaine = "42"
nombre = int(chaine)  # 42

# Conversion d'un float en entier
nombre_float = 3.99
nombre_entier = int(nombre_float)  # 3 (la partie décimale est tronquée)
```
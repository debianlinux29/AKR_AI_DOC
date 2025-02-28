Les structures de contrôle en Python permettent de diriger le flux d'exécution d'un programme en fonction de certaines conditions ou en répétant des blocs de code. Voici un aperçu des principales structures de contrôle disponibles en Python:

### 1. Structures de Contrôle Conditionnelles

Les structures conditionnelles permettent d'exécuter des blocs de code en fonction de conditions spécifiques.

**1. La structure if/elif/else**

La structure if permet d'exécuter un bloc de code si une condition est vraie,vous pouvez également utiliser elif pour vérifier d'autres conditions et else
pour exécuter un bloc de code si aucune des conditions précédentes n'est vraie.

**Exemple:**

```python
age = 18

if age < 18:
    print("Vous êtes mineur.")
elif age == 18:
    print("Vous avez 18 ans.")
else:
    print("Vous êtes majeur.")
```

Les conditions dans les structures if/elif peuvent utiliser des opérateurs de comparaison (comme == , != , > , < , >= , <=) pour évaluer des expressions.

else ne prends pas des opérateurs de comparaison.

### 2. Structures de Boucle

Les boucles permettent de répéter un bloc de code plusieurs fois.

**1. boucle for**

La boucle for est utilisée pour itérer sur une séquence (comme une liste, un tuple ou une chaîne de caractères).

**Exemple:**

```python
fruits = ['pomme', 'banane', 'cerise']

for fruit in fruits:
    print(fruit)
```

**2. boucle while**

La boucle while continue d'exécuter un bloc de code tant qu'une condition est vraie.

**Exemple:**

```python
compteur = 0

while compteur < 5:
    print("Compteur:", compteur)
    compteur += 1
```

### 3. Instructions de Contrôle de Flux

**1. instruction break**

L'instruction break permet de sortir d'une boucle prématurément.

**Exemple:**

```python
for i in range(10):
    if i == 5:
        break
    print(i)
```

**2. instruction continue**

L'instruction continue permet de sauter l'itération en cours et de passer à la suivante.

**Exemple:**

```python
for i in range(5):
    if i == 2:
        continue
    print(i)
```

**3. instruction pass**

L'instruction pass est un espace réservé qui ne fait rien. Elle est souvent utilisée lorsque vous avez besoin d'une structure de contrôle mais que vous ne voulez pas exécuter de code.

**Exemple:**

```python
if True:
    pass  # À compléter plus tard
```

### 4. Structures de Contrôle Imbriquées

Vous pouvez imbriquer des structures de contrôle, par exemple, avoir des boucles à l'intérieur de conditions ou vice versa.

**Exemple:**

```python
for i in range(3):
    if i % 2 == 0:
        print(i, "est pair")
    else:
        print(i, "est impair")
```
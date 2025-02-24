Le type str en Python représente une chaîne de caractères, qui est une séquence de caractères Unicode. Les chaînes de caractères sont utilisées pour stocker et manipuler du texte.

### 1. Caractéristiques du Type 

1. **Séquence de Caractères**: Une chaîne de caractères est une séquence ordonnée de caractères, qui peut inclure des lettres, des chiffres, des symboles et des espaces.

2. **Immutabilité**: Les chaînes de caractères en Python sont immuables, ce qui signifie que, une fois créées, elles ne peuvent pas être modifiées. Toute opération qui semble modifier une chaîne de caractères renvoie en réalité une nouvelle chaîne.

3. **Délimitation**: Les chaînes peuvent être définies en utilisant (des guillemets simples, des guillemets doubles, des guillemets triples pour les chaînes multilignes):

    Exemples:
    
    ```python
    chaine1 = 'Bonjour'
    chaine2 = "Python"
    chaine_multiligne = """Ceci est une chaîne
    qui s'étend sur plusieurs lignes."""
    chaine_multiligne = '''Ceci est une chaîne
    qui s'étend sur plusieurs lignes.'''
    ```

### 2. Opérations sur les Chaînes de Caractères

**Concaténation:** (Combiner deux chaînes)

**Répétition:** (Répéter une chaîne un certain nombre de fois.)

**Indexation:** Accéder à un caractère spécifique dans la chaîne.

**Slicing:** Extraire une sous-chaîne.

**Exemples d'Opérations:**

```python
# Déclaration de chaînes
chaine1 = "Bonjour"
chaine2 = " tout le monde"

# Concaténation
chaine3 = chaine1 + chaine2  # "Bonjour tout le monde"

# Répétition
chaine_repetee = chaine1 * 3  # "BonjourBonjourBonjour"

# Indexation
premier_caractere = chaine1[0]  # 'B'
dernier_caractere = chaine1[-1]  # 'r'

# Slicing
sous_chaine = chaine1[1:4]  # "onj" (caractères de l'index 1 à 3)
```

### 3. Méthodes des Chaînes

Python fournit de nombreuses méthodes intégrées pour manipuler les chaînes de caractères. Voici quelques-unes des plus courantes :

```python
len() # Renvoie la longueur de la chaîne.
str.lower() # Convertit la chaîne en minuscules.
str.upper() # Convertit la chaîne en majuscules.
str.strip() # Supprime les espaces au début et à la fin de la chaîne.
str.split() # Divise la chaîne en une liste de sous-chaînes.
str.replace(old, new) # Remplace une sous-chaîne par une autre.
```

**Exemples:**

```python
texte = "  Bonjour, Python!  "

# Longueur de la chaîne
longueur = len(texte)  # 18

# Conversion en minuscules
texte_minuscule = texte.lower()  # "  bonjour, python!  "

# Conversion en majuscules
texte_majuscule = texte.upper()  # "  BONJOUR, PYTHON!  "

# Suppression des espaces
texte_nettoye = texte.strip()  # "Bonjour, Python!"

# Division de la chaîne (renvoie un list)
mots = texte_nettoye.split(", ")  # ['Bonjour', 'Python!']

# Remplacement
texte_modifie = texte.replace("Python", "monde")  # "  Bonjour, monde!  "
```

### 4. Formatage de Chaînes

Python propose plusieurs façons de formater des chaînes:

**Exemples de Formatage:**

```python
nom = "Alice"
age = 30

# F-string (Python 3.6+)
message = f"{nom} a {age} ans."  # "Alice a 30 ans."

# str.format()
message2 = "{} a {} ans.".format(nom, age)  # "Alice a 30 ans."

# Formatage avec %
message3 = "%s a %d ans." % (nom, age)  # "Alice a 30 ans."
```
### Introduction à JSON

**JSON (JavaScript Object Notation)** est un format léger de stockage et d'échange de données, facile à lire et à écrire pour les humains, et facile à analyser et à générer pour les machines. Il est largement utilisé dans le développement web, notamment pour les API (Application Programming Interfaces) et les applications web, en raison de sa simplicité et de sa compatibilité avec de nombreux langages de programmation.

### 1. Caractéristiques de JSON

**Format Texte:** JSON est un format de texte qui peut être facilement lu et écrit par des humains. Il est également facile à analyser et à générer par des machines.

**Structure de Données:** JSON représente des données sous forme de paires clé-valeur, ce qui le rend similaire aux objets en JavaScript et aux dictionnaires en Python.

**Types de Données:** JSON prend en charge plusieurs types de données,

- Chaînes de caractères (strings)
- Nombres (numbers)
- Objets (objects) : collections de paires clé-valeur
- Tableaux (arrays) : listes ordonnées de valeurs
- Booléens (true/false)
- Null (null)

**Indépendance du Langage:** Bien que JSON soit dérivé de JavaScript, il est indépendant du langage et peut être utilisé avec de nombreux langages de programmation, y compris Python, Java, C#, PHP, et bien d'autres.

### 2. Syntaxe JSON

Voici un exemple de structure JSON:

```json
{
    "nom": "Alice",
    "age": 30,
    "ville": "Paris",
    "estEtudiant": false,
    "compétences": ["Python", "JavaScript", "SQL"],
    "adresse": {
        "rue": "123 Rue de Paris",
        "codePostal": "75001"
    }
}
```

Dans cet exemple :nom, age, ville, estEtudiant, compétences et adresse sont des clés.

Les valeurs associées peuvent être de différents types : chaîne de caractères, nombre, booléen, tableau, ou objet.

### 3. Manipulation de JSON en Python

pour travailler avec des données JSON. Voici quelques opérations courantes

- Convertir une chaîne JSON en [dict](../python/type_dict.md) Python :

```python
import json

# Chaîne JSON
json_data = '{"nom": "Alice", "age": 30}'

# Conversion en dictionnaire Python
data = json.loads(json_data)
print(data["nom"])  # Affiche: Alice
```

- Convertir un [dict](../python/type_dict.md) Python en chaîne JSON :

```python
import json

# Dictionnaire Python
data = {
    "nom": "Alice",
    "age": 30
}

# Conversion en chaîne JSON
json_data = json.dumps(data)
print(json_data)  # Affiche: {"nom": "Alice", "age": 30}
```
Une **REST API** (Representational State Transfer Application Programming Interface) est un type d'interface de programmation qui permet aux applications de communiquer entre elles sur Internet en utilisant le protocole HTTP. Les REST APIs sont largement utilisées pour créer des services web, permettant aux clients (comme des applications web ou mobiles) d'accéder et de manipuler des ressources sur un serveur.

### 1. Principes de Base des REST APIs

**Stateless:** Chaque requête envoyée à un serveur doit contenir toutes les informations nécessaires pour comprendre et traiter la demande. Le serveur ne conserve pas d'état entre les requêtes, ce qui signifie qu'il ne stocke pas d'informations sur les sessions des utilisateurs.

**Ressources:** Les ressources (données) sont identifiées par des URI (Uniform Resource Identifier). Par exemple, une ressource utilisateur pourrait être accessible via

```bash
https://api.example.com/users/1 # où 1 est l'identifiant de l'utilisateur.
```

**Méthodes HTTP:** Les REST APIs utilisent les méthodes HTTP pour effectuer des opérations sur les ressources :

- **GET**: Récupérer des données d'une ressource.
- **POST**: Créer une nouvelle ressource.
- **PUT**: Mettre à jour une ressource existante.
- **DELETE**: Supprimer une ressource.

**Représentations:** Les ressources peuvent être représentées dans différents formats, comme JSON (JavaScript Object Notation), XML (eXtensible Markup Language), ou HTML. JSON est le format le plus couramment utilisé en raison de sa légèreté et de sa facilité d'utilisation.

### 2. Exemples de Requêtes REST API

Voici quelques exemples de requêtes REST API utilisant curl (un outil en ligne de commande pour faire des requêtes HTTP.)

**GET**: Récupérer une liste d'utilisateurs.

```bash
curl -X GET https://api.example.com/users
```

**POST**: Créer un nouvel utilisateur.

```bash
curl -X POST https://api.example.com/users -H "Content-Type: application/json" -d '{"name": "Alice", "age": 30}'
```

**PUT**: Mettre à jour un utilisateur existant.

```bash
curl -X PUT https://api.example.com/users/1 -H "Content-Type: application/json" -d '{"name": "Alice", "age": 31}'
```

**DELETE**: Supprimer un utilisateur.

```bash
curl -X DELETE https://api.example.com/users/1
```
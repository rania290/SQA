# SQA
# Projet de Météo avec OpenWeatherMap

## Description
Ce projet permet de récupérer et d'afficher les données météorologiques d'une ville en utilisant l'API OpenWeatherMap. Il propose trois implémentations en JavaScript utilisant différentes bibliothèques pour effectuer des requêtes HTTP :
- `axios`
- `fetch`
- `request`

## Fonctionnalités
- Récupération des données météo : température, humidité et description du temps.
- Affichage des informations en console.
- Gestion des erreurs en cas d'échec de la requête.

## Prérequis
- Installation de Node.js
- Une clé API OpenWeatherMap (remplacez `API_KEY` dans le code par votre propre clé)

## Installation
1. Clonez ce dépôt :
   ```sh
   git clone https://github.com/votre-repo.git
   cd votre-repo
   ```
2. Installez les dépendances requises :
   ```sh
   npm install axios request
   ```

## Utilisation
Exécutez l'un des scripts suivants selon la bibliothèque choisie :

### Avec Axios
```sh
node weather-axios.js
```

### Avec Fetch
```sh
node weather-fetch.js
```

### Avec Request
```sh
node weather-request.js
```

## Exemple de Résultat
```
Description : ciel dégagé
Température : 25°C
Humidité : 60%
```

## Remarque
L'API OpenWeatherMap impose un quota de requêtes gratuites. Vérifiez votre consommation sur leur site officiel.

## Licence
Ce projet est sous licence MIT.


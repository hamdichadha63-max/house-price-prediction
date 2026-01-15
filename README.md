# Guide d'Installation et d'Exécution

## 1. Prérequis
Assurez-vous d'avoir Python installé sur votre machine.

## 2. Installation
Ouvrez un terminal dans le dossier du projet et installez les dépendances :
```bash
pip install -r backend/requirements.txt
```

## 3. Lancer le Projet

### Étape 1 : Démarrer l'API (Backend)
Ouvrez un terminal et lancez le serveur Flask :
```bash
python backend/app.py
```
*Le serveur démarrera sur `http://127.0.0.1:5000`*

### Étape 2 : Lancer l'Application (Frontend)
Ouvrez simplement le fichier `frontend/index.html` dans votre navigateur web (Chrome, Edge, Firefox).

*Note : Pour une meilleure expérience (et éviter les problèmes de CORS stricts de certains navigateurs fichiers locaux), il est recommandé de servir le frontend, mais l'API Flask est configurée pour permettre les requêtes locales.*

## 4. Utilisation
1. Remplissez le formulaire avec les détails de la maison.
2. Cliquez sur "Predict Price".
3. L'intelligence artificielle estimera la valeur de la maison instantanément.

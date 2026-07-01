# Mon-Projet-Data

## Création de l'environnement virtuel

```bash
python -m venv env
```

## Activation de l'environnement

### Git Bash

```bash
source env/Scripts/activate
```

### CMD

```cmd
env\Scripts\activate
```

### PowerShell

```powershell
.\env\Scripts\Activate.ps1
```

## Installation des dépendances

```bash
pip install -r requirements.txt
```

## Exécution du programme

Pour lancer le script principal :

```bash
python scripts/analyse.py
```

## Fichier requirements.txt

Le fichier `requirements.txt` contient la liste des packages installés ainsi que leur version, au format :

```text
nom_du_package==version
```

Exemple :

```text
pandas==3.0.3
matplotlib==3.11.0
numpy==2.5.0
```

Pour installer toutes les dépendances :

```bash
pip install -r requirements.txt
```

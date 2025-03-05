# Script - Gestionnaire de Scripts Bash

## Attention
Ceci est mon code perso sinon je suis avec guillaume


## Description
Ce script permet de gérer et d'exécuter facilement des scripts Bash (.sh) stockés dans un répertoire dédié. Il détecte automatiquement les fichiers avec l'extension `.sh` et permet à l'utilisateur de sélectionner celui qu'il souhaite exécuter.

## Fonctionnalités
- Recherche tous les fichiers `.sh` dans le répertoire `apprend`.
- Affiche une liste des scripts disponibles avec une numérotation.
- Permet à l'utilisateur de choisir un script à exécuter.
- Exécute le script sélectionné avec Bash.
- Vérifie si le choix de l'utilisateur est valide.

## Prérequis
- Un environnement Linux avec Bash installé.
- Des scripts Bash (.sh) présents dans le répertoire `apprend`.

## Installation
1. Clonez ce projet ou copiez le script sur votre machine.
2. Assurez-vous que le fichier `gestionnaire.sh` est exécutable :
   ```bash
   chmod +x gestionnaire.sh
   ```
3. Créez un dossier `apprend` si ce n'est pas déjà fait :
   ```bash
   mkdir -p apprend
   ```
4. Ajoutez vos scripts `.sh` dans le dossier `apprend`.

## Utilisation
1. Exécutez le script de gestion :
   ```bash
   ./gestionnaire.sh
   ```
2. Une liste des scripts disponibles s'affichera.
3. Saisissez le numéro du script que vous souhaitez exécuter.
4. Le script sélectionné s'exécutera automatiquement.

## Exemple de sortie
```bash
Sélectionnez un script à exécuter :
1) script1.sh
2) script2.sh
3) script3.sh

Entrez le numéro du script : 2
Exécution de script2.sh...
```

## Remarque
Si aucun script `.sh` n'est trouvé, un message d'erreur sera affiché et l'exécution du gestionnaire s'arrêtera.

## Auteur
- Guillaume & Collaborateurs


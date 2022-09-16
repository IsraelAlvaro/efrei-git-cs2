# Projet de test pour l'apprentissage de Git

Ceci est un projet de test\
pour l'apprentissage de Git.
\n Liste des commandes vues: \n
git init: créer un dépot git ou réinitialiser un dépôt existant \n
git config: options de base du git \n
git status: voir l'état actuel \n
git log: voir l'historique des commit \n
git add: ajouter des fichiers \n
git commit: enregistrer les changemens effectués au dépôt. -m "message", --amend -m "modifie le message" \n
git show: \n
git reset: réinitialiser à un moment précis, --soft "tag"\n
git tag: créer un tag pour un commit, -a "nom du tag", -d "nom du tag" pour supprimer \n
# Projet de test pour l'apprentissage de Git
 
Ceci est un projet de test\
pour l'apprentissage de Git.
 
## Commandes importantes à retenir
 
```bash
git init
```
Permet d'initialiser un dépôt git (attention de bien vérifier l'endroit où l'on se trouve dans le terminal !).
 
```bash
git status
```
Permet de vérifier l'état de la gestion actuelle du code source.
 
```bash
git config [--global] user.email <e-mail>
git config [--global] user.name <name>
```
Permet de définir les informations de l'utilisateur courant pour Git, pour le projet en cours.
 
```bash
git add <fichier>
git add .
```
Permet d'ajouter un fichier ou tous les fichiers (.) à l'historique de suivi des fichiers de Git.
 
```bash
git restore <fichier>
```
Permet de revenir à un état du fichier avant les dernières modifications apportées (entre le dernier commit et l'état présent).
 
```bash
git restore --staged <fichier>
```
Permet de retirer temporairement un fichier (unstage) de l'historique de suivi des fichiers de git
 
```bash
git commit -m <message>
```
Permet de créer un commit, une image des modifications apportées sur les fichiers et dossiers contenus dans le dossier suivi par Git.
 
```bash
git rm --cached <fichier>
```
Permet de retirer un fichier commité de l'historique de suivi des fichiers de Git.
 
```bash
git reset [--soft] [--hard] <commit hash>
```
Permet de revenir à l'état du code source correspondant au commit renseigné ; --soft conserve les modifications apportées aux fichiers, --hard les supprime. La valeur par défaut est --soft.
 
```bash
git log
```
Permet de voir l'historique des commits de la présente branche du présent dépôt.
 
```bash
git show
```
Permet d'afficher les informations relatives et détaillées du dernier commit en date.
 
```bash
git tag -a <version> -m <message> <commit to which apply the tag>
```
Permet d'attribuer un numéro de version à un commit donné (si "commit" est renseigné, ou au dernier commit par défaut). 
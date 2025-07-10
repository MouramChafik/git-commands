# 🧠 Git – Toutes les Commandes et Utilisations

> Ce fichier contient une liste complète des commandes **Git**, bien organisées.

---

## 📦 Initialisation et Configuration

```
git init                                   Crée un nouveau dépôt Git local.
git config --global user.name "Nom"        Définit le nom de l'utilisateur.
git config --global user.email "email"     Définit l'e-mail de l'utilisateur.
git config --list                          Affiche la configuration actuelle.
```

---

## 🔍 Statut et Historique

```
git status                 Affiche l'état des fichiers du dépôt.
git log                    Affiche l'historique des commits.
git log --oneline          Affiche un résumé des commits.
git show                   Affiche les informations d'un commit.
```

---

## 📁 Ajout et Validation

```
git add <fichier>          Ajoute un fichier à l'index.
git add .                  Ajoute tous les fichiers modifiés.
git add -u                 Ajoute les fichiers suivis modifiés.
git commit -m "msg"        Crée un commit avec un message.
git commit -am "msg"       Ajoute et commit les fichiers suivis.
```

---

## 🔁 Branches

```
git branch                Liste les branches locales.
git branch <nom>          Crée une nouvelle branche.
git branch -d <nom>       Supprime une branche locale.
git checkout <branche>    Bascule sur une branche.
git checkout -b <nom>     Crée puis bascule sur une branche.
git switch <branche>      Bascule sur une branche (nouveau).
git switch -c <nom>       Crée puis bascule sur une branche.
```

---

## 🌐 Dépôt Distant

```
git remote add origin <url>     Ajoute un dépôt distant.
git remote -v                   Affiche les dépôts distants.
git push -u origin <branche>    Envoie la branche avec suivi.
git push                        Pousse les commits vers le dépôt distant.
git pull                        Récupère et fusionne depuis le dépôt distant.
git fetch                       Récupère les modifications sans les fusionner.
git clone <url>                 Clone un dépôt distant.
```

---

## 🧽 Réinitialisation et Annulation

```
git restore <fichier>           Annule les modifications non indexées.
git reset <fichier>             Retire un fichier de l'index.
git reset --hard                Réinitialise tout l'état du projet.
git revert <hash>               Annule un commit avec un commit inverse.
git checkout -- <fichier>       Ancienne méthode pour annuler un fichier.
```

---

## 🧪 Différences

```
git diff                            Montre les changements non indexés.
git diff --staged                   Montre les changements en attente de commit.
git diff <branche1> <branche2>      Compare deux branches.
```

---

## 📄 Suivi des Fichiers

```
git ls-files                   Liste les fichiers suivis par Git.
git clean -f                   Supprime les fichiers non suivis.
```

---

## ⛔ Commandes Avancées

```
git stash                      Sauvegarde temporairement les modifications.
git stash list                 Liste les stashes.
git stash apply                Réapplique les changements stockés.
git stash drop                 Supprime un stash.
git cherry-pick <hash>         Applique un commit spécifique.
git rebase <branche>           Rejoue l’historique sur une autre base.
git rebase -i HEAD~n           Rebase interactif sur les n derniers commits.
```

---

## 🏷️ Tags

```
git tag                        Liste les tags.
git tag <nom>                  Crée un tag.
git tag -a <nom> -m "msg"      Crée un tag annoté.
git push origin <tag>          Pousse un tag.
```

---

## 🆘 Aide

```
git help                       Affiche l’aide générale.
git help <commande>            Affiche l’aide pour une commande.
```

---

## ✅ Exemple de Workflow

```
git init
git add .
git commit -m "Initial commit"
git remote add origin <url>
git push -u origin main
```

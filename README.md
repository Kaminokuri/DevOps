## Installation de Git
```bash
# Ubuntu/Debian
sudo apt update
sudo apt install git

# Vérification
git --version

## Exemple : tableau des commandes (modèle)
Tu complètes la colonne Description avec tes mots :

```md
| Commande | Description |
|---|---|
| `git clone <url>` | Cloner le dépôt distant en local |
| `git status` | Voir les fichiers modifiés / indexés |
| `git add <fichier>` | Ajouter au staging |
| `git commit -m "msg"` | Créer un commit |
| `git switch -c develop` | Créer + basculer sur la branche develop |
| `git push -u origin develop` | Pousser la branche develop sur GitHub |
| `git merge develop` | Fusionner develop dans la branche courante |
| `git mv a b` | Renommer un fichier en gardant l’historique |
| `git rm <fichier>` | Supprimer un fichier versionné |

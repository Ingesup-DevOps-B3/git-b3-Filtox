
## Exercice 1: Authentification

- Générer une paire de clef SSH

![ssh](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/ssh.png)

- Pousser votre clef publique dans votre profile Github

![ssh_push](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/push_cle.png)

- Configurer votre git local en rajoutant
  - username
  - email

![config](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/git_config.png)

## Exercice 2 : Création d'un Repo Github

- Initialiser votre dépôt local

![init](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/init.png)

- Faire pointer le dépôt local sur un dépôt distant (Remote)

![remote](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/remote.png)

- Vérifier le dépôt distant

![status](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/status.png)

- Cloner le repository

![pull](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/pull.png)

## Exercice 3 : Modification du Projet CLI

- Modifier un fichier déjà existant
  - Ajouter le port 2222 pour l'host **Tyrell**
  - Set le niveau de log à `INFO` pour tout les hosts finissant en **ell**

![modif](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/modif.png)

- Consulter le statut et les différences

![diff](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/diff_status.png)

- Commiter vos modifications

![commit](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/commit.png)

- Ajouter un fichier `diff.txt` et commencer à le tracker

![diff_txt](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/difftxt.png)

  - Expliquer rapidement la différence entre `git pull` et `git fetch`

La commande git pull est en fait la combinaison de deux autres commandes, git fetch suivie de git merge. git-fetch télécharge les objets et références depuis un autre dépôt.

- Pousser vos modifications

![push](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/push.png)

## Exercice 4 : Modification du projet GUI

- Modifier le fichier `config` en se connectant sur l'interface Github
  - Rajouter :
```sh
Host stark
    HostName 127.0.0.1
    User john
    Port 6666
    IdentityFile ~/.ssh/stark.key
```

![host](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/host.png)

## Exervice 5 : Branching et Merging

- Cloner le repo de votre voisin
- Assurer vous d'avoir un repo à jour
- Créer une nouvelle branche et basculer dessus
  - Branch name : change_throne 

![branche](https://github.com/Ingesup-DevOps-B3/git-b3-Filtox/blob/main/images/branch.png)

- Modifier la configuration SSH 
  -  Modifier le user `daenerys` pour `john`dans l'host `targaryen`
  -  Supprimer le user `john`dans l'host `stark`
-  Commiter et pousser la modification dans la nouvelle branche
-  Créer une Pull Request sur Github
-  Merger les 2 branches sur votre repo. (Avec les modifications de votre binome)

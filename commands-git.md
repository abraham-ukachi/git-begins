# `commands-git`

Voici les **commandes git** qui permettent de:
 
## Cloner un repo
> git clone <u>*__url du repo__*</u>

```sh
git clone https://github.com/abraham-ukachi/git-begins.git
```

## Les 3 commandes de push (dans l'ordre)

### 1ère commande de push
> git add <u>*__fichier__*</u>

```sh
git add README.md
```

### 2ème commande de push
> git commit <**-m** <u>*__option__*</u>> <u>*__message__*</u>

```sh
git commit -m "Initial commit"
```

### 3ème commande de push
> git push <**-u** <u>*__option__*</u>> [<<u>*__branch__*</u>>]

```sh
git push
```
ou 

```sh
git push -u origin main
```

## La commande de pull
> git pull <<u>*__option__*</u>> [<<u>*__url du repo__*</u>>]

La commande que permet de **pull**:

```sh
git pull
```

<<<<<<< HEAD
    
=======
# Creation de branche

La commande qui permet de creer une branche sur [github](https://github.com) est la suivante:

> git branch *__nom de la branche__*

```sh
git branch add-create-branch-command
```    

Pour switcher d'une branche a une autre:

> git branch checkout *__nom de la branche__*

```sh
git branch checkout main
```

>>>>>>> add-create-branch-command

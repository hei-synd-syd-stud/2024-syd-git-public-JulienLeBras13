# Answers of Julien Le Bras JulienLeBras13

## Basics

### Task 1

repo
|_.git (hiden folder) ==> le dossier `.git` est le cœur de Git dans un dépôt. C’est grâce à lui que Git peut gérer les versions, les branches, les fusions, et toutes les opérations nécessaires au contrôle de version.
|_img (folder) ==> contiens l'image gitgraph
|_answer.md ==> fichier markdown ou se trouve les réponses aux questions du laboratoires

### Task 2

Apparition d'un "untracked file", il s'agit du fichier "README.md". Il est "untracked" car le fichier viens d'être créer.

### Task 3

Il y a un fichier (README.md) qui est staged et un qui ne l'est pas (answer.md). Ce qui veux dire que seulement le fichier README.md serra commit.

### Task 4

On vois les changement apportés au fichier README.md ne sont pas "staged", la version du fichier README.md "staged" est le fichier vide.

### Task 5

Que signifie la chaîne de caractères au début ?

Le commit `f5d4a3c` (hash abrégé) est le commit le plus récent sur la branche `main`.

Que signifient HEAD et main ?

`HEAD -> main` indique que `HEAD` pointe vers `main`, ce qui signifie que nous sommes actuellement sur la branche principale.

Qu’est-ce qui se trouve après les parenthèses ?

Le message du commit est `Added user authentication feature`, ce qui décrit brièvement ce que ce commit ajoute ou modifie.

### Task 6

Lors du retour sur le commit "Initial commit" le dossier s'est retrouvé dans l'état dans lequel il était lors de ce commit, cad answer.md inchangé et README.md non créer.

Lors du retour au dernier commit le dossier à retrouver sont état de ce dernier commit, fichier answer.md modifier et README.md créer et modifier.

## Gitgraph

### Task 7

1) branch "develop"

2) git hash abrégé "baa6795"

3) changement 

4) Autheur

5) version

6) commit final de la branch develop

7) commit de la branch feature-auth

8) commit de la branch main

9) branch develop

10) branch main

![Gitgraph](img/gitgraph.svg)
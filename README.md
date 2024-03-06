![Logo](https://i.imgur.com/8yebMs8.jpeg)

# A propos :

Makegit-Simple à pour but de vous donner les ressources pour utiliser git et GitHub de manière fluide et intuitive. C'est une sorte de "Cheat Sheet" qui regroupe tous les éléments que vous allez avoir besoin pour avoir une utilisation propre de GitHub.


### Installation de GitHub

Pour commencer à utiliser GitHub et utiliser des commandes Git il vous faudra d'abord l'installer à partir du site officiel : [Site officiel de Git](https://git-scm.com/downloads).

🎉 Une fois installer et Git ajouté au PATH, vous pouvez utilisez les commandes git.

### Cloner un projet

Pour cloner un repo public pour il faut utiliser la commandes

```
git clone URL_DU_REPO
```
Vous trouverez l'Url d'un repo public en cliquant sur "code" et en sélectionnant https :

![Logo](https://i.imgur.com/6hGpGFx.png)


Si vous souhaitez cloner un repo privé ou via SSH il vous faut créer et enregistrer une clé SSH et la manipulation sera la même.

### Création d'une clé SSH

La première chose à faire est de suivre les étapes pour votre système d'exploitation que vous pouvez retrouver ici : [Site officiel de GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

Vous pouvez choisir entre ed25519 ou RSA pour le format de votre clé SSH.

Suivez les étapes et une fois fait, afficher votre clé publique dans le terminal avec :

```
cat chemin/vers/.ssh/id_rsa.pub
```

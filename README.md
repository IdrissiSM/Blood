# BLOOD++ : Save Lives, Donate Blood – The Power is in Your Hands!

### Technologies

![XML](https://img.shields.io/badge/XML-FF6600?style=for-the-badge&labelColor=black&logo=xml&logoColor=FF6600)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&labelColor=black&logo=java&logoColor=007396)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&labelColor=black&logo=sqlite&logoColor=003B57)

## POURQUOI CE PROJET ?

Les réserves nationales de sang ne permettent de couvrir que quelques jours de besoins. La solidarité et l'entraide sont des traits communs à tous les Marocains. Pourtant, malgré la bonne volonté, beaucoup d'entre nous ne savent pas où aller ni comment s'y prendre. Blood++ est donc là pour répondre à toutes ces questions relatives au don de sang et vous indiquer le centre de prélèvement le plus proche. Blood++ est également à votre disposition lorsque vous avez besoin de sang pour publier votre annonce et la partager au plus grand nombre au Maroc.

On a fait cette appli dans un projet du dev web. et on a penser a etendre l'application en mobile aussi.

Cette idée d'application existe au Maroc C'est une application appelée "Leena" mais le point faible de cette application est sa petite portée des citoyens. Nous espérons qu'après avoir développé cette application très basique pour continuer et ajouter plus de fonctionnalités et la rendre disponible pour aider plus de personnes.


## 📹 VIDEO PRESENTATIF DE L'APP : [WATCH DEMO](https://drive.google.com/drive/folders/1NkY7szu__hMYTEPLa_OXX0Bg431wOw0S?usp=share_link)


## APP OVERVIEW :

![LOGIN](https://github.com/IdrissiSM/Blood/blob/main/Blood++/captures/Blood++_1.png)
![LOGIN](https://github.com/IdrissiSM/Blood/blob/main/Blood++/captures/Blood++_2.png)


## DESCRIPTION DU UX USER-EXPERIENCE :

Au premier moment, nous ouvrons l'application une interface (rouge) avec le logo de l'application au milieu, après 4 secondes, une intent commence et nous redirige vers l'interface de connexion (inscrire: Login/sign up) Soit vous connectez si vous avez un compte Ou vous créez un nouveau compte si c'est votre première fois. 

Après avoir fait cela, une autre intent commence et nous emmène sur la page principale qui n'est qu'une liste de donateurs `(car l'objectif principal de l'application est de faciliter la portée des personnes au dons de sang, nous avons fait notre page d'accueil)`. Dans la même page, nous avons en haut une dropdown qui a un autre élément qui nous amène aux demandes de sang (requests) pour voir ce que les autres demandent et quel type de sang ils ont besoin et toutes les informations nécessaires pour les atteindre.

Dans cette page principale, vous pouvez remarquer le bouton "Supprimer" (delete) apparaissant pour quelques éléments, ce bouton Supprimer est juste pour l'utilisateur actuel de l'application qui a le droit de supprimer sa demande quand il le souhaite. Pour chaque personne (item), nous avons son profil avec des informations détaillées et un bouton pour appeler cette personne directement en utilisant une intent explicite. Il existe également une autre interface qui est le profil utilisateur actuel qui peut mettre à jour ses données à tout moment et les enregistrer dans la base de données.

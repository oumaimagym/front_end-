# AssignmentApp : on a rajouté 20 fonctionnalités
Done by oumaima gym
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.3.

## 1.
j'ai ajouté bootstrap et un navbar contenant toutes les routes accesibles au utilisateurs connecté(selon son role+droits).
## 2.
j'ai ajouté Rendu la présentation plus jolie, notamment  les assignments dans une table angular material, avec l'élément paginator pour faire la pagination.
## 3.
j'ai ajouté implementé un deuxieme exemple sur la meme page, notamment  les assignments dans une table angular material de hauteur fixe, qui scrolle les éléments, mais qui laisse le header fixe("sticky row")
## 4.
 la table a gauche(exemple du paginator) on a les colonnes triables (avecla vue)
## 5.
j'ai ajouté le surlignage de la ligne sur laquelle on déplace la souris (dans les deux exemple paginator et sticky row)
## 6.
Dans l'exemple  a droite j'ai ajouté une icône dans une colonne supplémentaire à droite, et quand on clique dessus on a le détail. 
## 7.
Dans l'exemple  a droit on a rajouté une colonne supplémentaire dans le tableau qui présente la liste, et si on clique dessus ça supprime directement (sans passer par le détail) la suppression se fait sans demander l'avis a l'utilisateur
## 8.
j'ai géreé la connexion login/password avec des variables ( ona l'a fait meme dans le backend avec JWT ou elle etait fonctionnelle, mais dans Heroku ca n'a pas fonctinné)
## 9.
On a codée une interface graphique de connexion
## 10.
On a codée une interface graphique d'inscription
## 11.
j'ai codée une fonction/route  de deconnexion
## 12.
j'ai codée une interface graphique de reception
## 13.
j'ai codé une interface graphique de perte(route not found, elle fonctionne que si on est connecté sinon on est redirigé vers la reception)
## 14.
En haut de l'écran, un bouton "d'ajoue" qui n'apparait que si on est connecté, 
## 15.
En haut de l'écran, un bouton "peupler bd" qui apparait que si on n'est connecté. 
## 16.
En haut de l'écran, text "nom prenom user" qui apparait que si on est connecté sur l'icone de l'id. 
## 17.
On ne pourra editer et supprimer un assignment que si on est connecté en admin. Les boutons serons grisés pour ne pas proposer l'option si on n'a pas le droit. 
## 18.
ona rajouté des composants material dans toutes les pages(edit assignments, add asginments, login, signup ...)
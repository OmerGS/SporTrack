####################################

Commentaire du codes et des screenshot :

Nom du screenshot : commentaire


Body (DIV) : Toutes les pages HTML de notre site sont fabriquées en utilisant les blocs <div> cela nous permet d'avoir une liberté importante sur le design de la page. Il y a une seule exception la page (tos.html) qui est fait avec des <section> pour des soucis de praticité.

CSS : 
-> Toutes les pages CSS sont fait avec des class (sauf quelque blocs). On a utiliser des paramètre ".[nom de la classe]:hover" pour ajouter un effet lorsque la souris passe sur le blocs. (https://developer.mozilla.org/fr/docs/Web/CSS/:hover)

-> On a aussi utiliser les paramètre suivant :
	- ".[nom de la classe]:focus" pour ajouter un effet lors de la sélection d'un input dans la page "inscrire.html". (https://developer.mozilla.org/fr/docs/Web/CSS/:focus)
	
	- "@media screen and (max-width: 767px)" qui permet de faire du responsive, c'est à dire de modifier l'affichage de la page web en fonction de l'appareil utilisé.
	
	- "@keyframes [variable]" qui nous a permi d'animer les arrières plans de la page (index.html) (https://www.w3schools.com/css/css3_animations.asp)
 
Page d'acceuil (edge) : La page principal de notre site, on atteri directement dessus quand on rentre sur le localhost car le fichier à le nom de "index.html" donc le serveur nous envoie directement dessus.

Profil (edge) : Les informations de (connection.html) sont transmis grâce à la barre de l'utl pour l'instant. Comme ce n'est pas très securisée l'année prochaine on les feras passé par method post pour qu'on puisse pas voir les informations. Page de profil des utilisateur, permet de visualiser les courbes inserer via les fichiers JSON (à faire en BUT2) et aussi permet d'acceder au informations de l'utilisateur et de les modifier. (Screenshot "Profil (Modification Infos Perso) (edge)")

Profil Envoie de Fichier (edge) : Cette section de notre site permet d'envoyer des fichiers JSON au serveur, ce qui va permettre de les "lire" et d'en faire une synthèse.

Se Connecter (edge) : Page de connection fait avec un formulaire (html) qui transmet les informations par l'url à la page profil.html.

Se connecter (responsive) (edge) , Se Connecter (Galaxy), Se Connecter (iPhone), Se Connecter (Nest Hub Max) sont des exemples d'affichage du site internet dans d'autres format que les écrans de pc "clasique".


##########################################

Pour le codage on a utiliser Visual Studio Code avec pour Romain : le serveur localhost Wamp64 et pour Omer : le serveur localhost de VS Code et Mamp.


On a testé SportTrack sur Microsoft Edge et Google Chrome. 

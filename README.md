# Bid_Cars

Plateforme d'enchère en ligne de véhicule. <br>
Technologies utilisées : PHP Vanilla / CSS / HTML / MySQL <br>
Premier projet PHP

### Vue générale du site

Voici la vue générale du site pour un utilisateur non connecté.
Ce dernier peut accéder à l'ensemble du site, ajout d'annonce compris. Seul l'action d'enchérir est reservé aux membres inscrits et connectés.
![vue_generale](https://user-images.githubusercontent.com/78733270/114773700-aaf44d00-9d6f-11eb-81b8-e53850a82bf1.PNG)

### Vue des annonces

On peut y voir la marque du véhicule, le modèle, le kilométrage, l'année de mise en circulation ainsi que le prix actuel (variable selon les enchères).
L'utilisateur peut accéder au détail de l'annonce et à la section enchère en cliquant sur "Voir l'annonce".
![Annonces](https://user-images.githubusercontent.com/78733270/114774098-1ccc9680-9d70-11eb-819a-59886ca6374d.PNG)

### Vue détail d'une annonce
C'est ici que l'utilisateur accède à l'ensemble de l'annonce. Il voit l'ensemble des détails du véhicule et peut enchérir s'il est connecté.
![detail_annonce](https://user-images.githubusercontent.com/78733270/114774326-5d2c1480-9d70-11eb-81f2-43a113bbbf80.PNG)

S'il n'est pas connecté, le champ d'enchère ne sera pas disponible et un texte l'invitera à se connecter.
![connexion_enchere](https://user-images.githubusercontent.com/78733270/114774935-01ae5680-9d71-11eb-8d4b-e2505b3fe13a.PNG)

### Vue du champ permettant de saisir l'enchère
C'est ici que l'utilisateur peut saisir le montant de son enchère. Il y voit le prix actuel et le champ contient un placeholder pour lui rappeler que son enchère doit être supérieure au montant actuel. (varie automatiquement en fonction du montant actuel)
![input_enchere](https://user-images.githubusercontent.com/78733270/114774487-88aeff00-9d70-11eb-99a3-5ce61ad9cb6f.PNG)

### Saisie d'un montant 

![saisie_montant_enchere](https://user-images.githubusercontent.com/78733270/114774680-b6944380-9d70-11eb-90cf-017d4d34d853.PNG)

### Vue après saisie d'enchère
On peut voir que le montant actuel a bien été modifié ainsi que le placeholder du champ d'enchère.
![affichage_apres_enchere](https://user-images.githubusercontent.com/78733270/114774768-d166b800-9d70-11eb-9f22-7e54f9fe8b26.PNG)

Le montant apparaîssant sur l'aperçu de l'annonce a lui aussi été modifié.

![annonce_home_apres_enchere](https://user-images.githubusercontent.com/78733270/114774815-e3485b00-9d70-11eb-85d2-7443800d610f.PNG)

















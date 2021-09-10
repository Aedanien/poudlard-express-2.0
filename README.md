Objectif : avoir un service permettant d'afficher les 4 maisons de Poudlard de la franchise Harry Potter avec Flask et Json en premier temps, puis en bdd mysql, dans un container different de l'app grace à un docker-compose.yml

Index() : fonction permettant d'afficher la page d'accueil du service, ou l'ont retrouve une version minimisée des maisons

get_maison_id(id) permet de passer au template d'une maison, ou l'on retrouve toutes les informations de la dite page.

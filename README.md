# Tp4

Vous devez produire une application à l'aide du framework SpringBoot au backend ainsi que du framework React au frontend.

## Backend

### 1. Date de remise:  Mardi le 2 Mai à 9h00

### 2. Description:  Ce travail compte pour 20% de la note finale et est à double seuil.

### 3. Retard: Tout retard entraîne une pénalité de 10% par jour jusqu'à concurrence de 5 jours.  La note de 0 est attribué si ce délai est dépassé.

####	Dans ce travail pratique vous allez mettre en pratique les notions suivantes 

•	Programmation java en utilisant le framework SpringData et une base de données H2 en mémoire. Vous devrez implanter les fonctionnalités suivantes tout en suivant le modèle des couches présentées en classe ainsi que la couche présentation à l’aide du framework React et du framework Spring Boot pour les REST services.

•	Ajout de tous les types de documents à la bibliothèque (Livre, Cd, DVD)

•	Recherche d’un document selon les critères suivant :  Titre, auteur, année.  Chaque critère est optionnel.  Pour le titre, on doit faire une recherche qui permette qu’elle ne soit pas exacte.  Par exemple, si le titre d’un livre est : « Les parapluies sont disparus », on devra pouvoir obtenir le document avec les critères de recherche contenant simplement le mot « parapluies » ou le mot « disparus ».

•	L’emprunt d’un document en tenant compte s’il reste au moins un exemplaire de disponible.  L’interface ne doit PAS CONTENIR d’id de clients.  ie que vous ne devez pas utiliser les ID au niveau de l’interface utilisateur pour effectuer un emprunt.  L'emprunt doit être effectué en utilisant celui qui est connecté. (voir le dernier point)

•	Le retour d’un document emprunté.

•	Le client doit pouvoir obtenir la liste de ses emprunts, les dates auxquelles il doit retourner chacun des documents empruntés.

•	Vous devrez fournir une interface web à l’aide de React permettant d’enregistrer un client, enregistrer un nouveau livre, cd, dvd, emprunter un livre, cd, dvd et retourner un livre, cd, dvd.  De plus on doit pouvoir voir la liste des clients ainsi que leurs emprunts.

•	Vous n’avez pas à produire la gestion des amendes.

•	Sur le ‘landing page’, vous pouvez me donner une ‘liste déroulante’ ou des boutons permettant de choisir le type d’utilisateur ET l’utilisateur d’une session.  Autrement dit, quand vous allez créer des utilisateurs, ceux-ci se retrouveront sur le 'landing page' afin que l'on puisse choisir l'utilisateur avec lequel on veut travailler.



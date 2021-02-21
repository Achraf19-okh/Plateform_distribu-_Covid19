# Plateform_distribu-_Covid19
la réalisation d'une plateforme temps réel permettant la mesure du temps du contrôle et la manipulation des mesures prises par différents capteurs.
la plateforme temps réel distribuée à base des systèmes multi-agents permettra en premier lieu l'enregistrement de ces mesures, température, pression et volume, reçues périodiquement toutes les 2 secondes dans une base de données et en second lieu la récupération et l'affichage instantanée des mesures ainsi que leur historique d'évolution sous forme des graphes temporelles.
A noter que, chaque mesure appartient à un patient et il faudra un identifiant et mot de passe pour accéder à la plateforme.
# l'application que nous avons réalisé : 
![img1](https://user-images.githubusercontent.com/61116467/108626211-55768080-744f-11eb-83a1-43969568ec64.png)
Après le lancement de l’application, il est demandé de saisir le login et le mot de passe pour faire l’authentification, pour cela on utilise pour utilisateur : admin et mot de passe : admin123
![img2](https://user-images.githubusercontent.com/61116467/108626267-9373a480-744f-11eb-802f-eb7b8712def1.png)
![image](https://user-images.githubusercontent.com/61116467/108626295-ab4b2880-744f-11eb-84c0-8408b0f490a1.png)
![image](https://user-images.githubusercontent.com/61116467/108626311-cb7ae780-744f-11eb-8ef4-99edc216a8b6.png)

> La page où toutes les personnes enregistrées dans le système sont répertoriées et ne peuvent être gérées que par l'utilisateur administrateur.

![image](https://user-images.githubusercontent.com/61116467/108626443-7ee3dc00-7450-11eb-8784-a1ca65e37cb3.png)

En cliquant sur « view », on peut voir les détails d’une personne, on trouve un code barre (posibilité de l’imprimer ) ainsi que un tracking ID généré par le système , et la température de cette perrsonne.

![image](https://user-images.githubusercontent.com/61116467/108626459-96bb6000-7450-11eb-8c37-de83c4fc1beb.png)

> Le code à barres peut servir d’identification comme le Home Quarantine Pass (HQP), dans cette fonction, cela aidera à identifier facilement la personne en scannant le code à barres, ce qui signifie quand une personne entrera dans un certain établissement, l’établissement ne fournira qu’une unité informatique pour qu’au moins une personne puisse accéder au système et, en scannant la personne, l’identification d’une personne s’affichera automatiquement et le personnel ne codera que la température de la personne, puis la sauvegardera dans la base de données, dans ce cas, la personne n’écrira pas ses informations sur la feuille de papier pour empêcher la propagation du virus d’une manière simple. La gestion de suivi/surveillance génère une liste de la personne qui est entrée dans un certain établissement alors que le gouvernement exige tous les établissements.

L’administrateur peut ajouter une nouvelle personne en indiquant ces informations à savoir (nom, prénom, adresse, zip code …) 

![image](https://user-images.githubusercontent.com/61116467/108626514-d5511a80-7450-11eb-8e70-25aa14779943.png)

# Users Page : 

![image](https://user-images.githubusercontent.com/61116467/108626541-ef8af880-7450-11eb-89b5-647a1ac46bcb.png)

# Records page :
>  La page où la liste des personnes qui sont entrées dans un certain établissement est répertoriée avec leurs informations. ID de suivi imprimable de la personne
L'identifiant imprimable à porter par les personnes et à utiliser pour les identifier lors de l'entrée dans un certain établissement en tenant compte la température qui ne doit pas être supérieur à 38°C.

![image](https://user-images.githubusercontent.com/61116467/108626562-09c4d680-7451-11eb-85eb-28a31c316769.png)

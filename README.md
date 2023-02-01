<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=PROJECT+API+CI%2FCD+WITH+PYTHON.+ILC" alt="Typing SVG" /></a>
  </P>
  
Le projet qu'on souhaite réaliser est un projet guidé pour la gestion CRUD d'un système de transaction, où on mettra en place ce que nous avons appris cette année avec le module de CI/CD

   ![Badge1](https://www.plunge.cloud/hs-fs/hubfs/cycle-devopsea2b.png?width=600&name=cycle-devops.png)



## Noms et prénoms du trinôme : 
  WALY Mouad, EL YOUSFI Mohammed et EZZAHID Sami


## Spécialité : 
  ILC.

## Le langage que nous souhaitons utiliser est :
  Python parce que, qui n'aime pas python!
  
## Fonctionnalités :

-Initialisation de l'application Flask

-Création d'une classe Personne qui permet de créer des objets Personne avec un nom et un sodle. Les objets Personne peuvent être converties en objets JSON, avoir des méthodes pour débiter ou créditer un compte, effectuer une transaction entre deux personnes.

-Méthode pour importer un fichier CSV de personnes

-Route pour afficher toutes les personnes et les transactions

-Route pour affichier les transactions sauvegargdées dans un fichier csv entre 2 personnes.

## Utilisation :

-Installation de flask avec :
    pip install flask
   
-Utilisez la route '/' pour afficher toutes les personnes et les transactions. 
    Dans un navigateur web : http://localhost:5000/ 
    Dans une commande CURL : ``curl -X GET "http://localhost:5000/"``
    
-Utilisez la route'/transactions' qui affiche la liste des transactions effectuées qui sont été lises du fichier transactions.csv.
    Dans un navigateur web : http://localhost:5000/transactions
    Dans une commande CURL : ``curl -X GET "http://localhost:5000/transactions"``
     
-Utlisiez la route '/person' qui permet d'ajouter une personne de type Person ayant un nom: name et un solde: balance.
     Executez cette fonction avec la commande CURL suivante :
              ``curl -X POST -d "name=Jerome&balance=5" http://localhost:5000/person``
              
-Utilisez la route 'person/id' qui permet de supprimer une personne en donnant son id
     Executez cette fonction avec la commande CURL suivante :
          ``curl -X DELETE http://localhost:5000/person/1``


## Vous trouverez ci-dessus les différentes actions dont on a besoin dans ce projet : 

App build :
![Generic badge](https://github.com/mouadw/4A_ILC_CRUD_API/actions/workflows/app_build.yml/badge.svg)

Build and push tag :
![Generic badge](https://github.com/mouadw/4A_ILC_CRUD_API/actions/workflows/build_push.yml/badge.svg)

Build docker image :
![Generic badge](https://github.com/mouadw/4A_ILC_CRUD_API/actions/workflows/buildDockerImage.yml/badge.svg)

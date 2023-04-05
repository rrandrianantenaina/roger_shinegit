# roger_shinegit

Voici le lien qui permet d’accéder au depot du test

https://github.com/rrandrianantenaina/roger_shinegit/tree/master

Lancer les commandes

git clone https://github.com/rrandrianantenaina/roger_shinegit.git

Entrer sur le repertoire roger_shinegit et
composer update
Modifier la ligne 29 du fichier .env pour Mettre à jour l’accès à la base de donnée
doctrine:database:create
php bin/console doctrine:migrations:migrate

Voici comment on appelle les api

GET
/apip/equipment
Récupérer la liste d’équipement

POST
/apip/equipment

Contenu
{
"name": "string",
"category": "string",
"number": "string",
"description": "string",
"createdAt": "2023-04-05T12:53:02.867Z",
"updatedAt": "2023-04-05T12:53:02.867Z"
}

Créer de l’équipement



GET
/apip/equipment/{id}
parametre:id
Récupérer un seul équipement




DELETE
/apip/equipment/{id}
parametre:id
Supprimer un équipement

PUT
/apip/equipment/{id}
parametre:id

Contenu
{
"name": "string",
"category": "string",
"number": "string",
"description": "string",
"createdAt": "2023-04-05T12:53:02.867Z",
"updatedAt": "2023-04-05T12:53:02.867Z"
}
Mettre à jours un equipement

PATCH
/apip/equipment/{id}
parametre:id

Contenu
{
"name": "string",
"category": "string",
"number": "string",
"description": "string",
"createdAt": "2023-04-05T12:53:02.867Z",
"updatedAt": "2023-04-05T12:53:02.867Z"
}

Mettre à jours un equipement



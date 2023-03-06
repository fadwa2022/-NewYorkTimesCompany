# NewYorkTimesCompany
## Installation de l'application
### Prérequis
* PHP 8.2 ou supérieur
* MySQL 5.7 ou supérieur
* Apache ou Nginx
### Étapes d'installation

1.Installation de WordPress.
2.Créez une nouvelle base de données MySQL et un utilisateur avec des privilèges pour cette base de données.
3.Dupliquez le fichier .env.example et renommez-le en .env.
4.Modifiez les paramètres de la base de données dans le fichier .env pour qu'ils correspondent à ceux de votre environnement de développement.
5.Ouvrez une console de commande et naviguez vers le répertoire de l'application.
6.Exécutez la commande composer install pour installer les dépendances.
7.Exécutez la commande php artisan key:generate pour générer une nouvelle clé de sécurité pour l'application.
8.Exécutez la commande php artisan migrate pour créer les tables de la base de données.
9.Exécutez la commande php artisan serve pour lancer le serveur web intégré.



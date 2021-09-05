# AuthmePHPanel
### Panel de control PHP des registre du plugin [Authme](https://www.spigotmc.org/resources/authmereloaded.6269/) pour votre serveur minecraft.

## Prérequis :
- [x] Avoir un serveur qui gère du MySQL sur votre site ex.(PhpMyadmin, Mariadb).
- [X] Configurer votre plugin Authme en mode **MYSQL** dans le fichier **config.yml**
- [X] Créer un identifiant pour la base de données Authme **n'utilise pas vos identifiants root** !

## Avertissement :
- [X] Notre code ne contient aucun système de permission ne pas laisser n'importe qui l'utiliser !
- [X] Depuis le panel vous pouvez supprimer, modifier et lire les informations d'enregistrement des joueurs et est donc recommandé de hashé les mots de passe !

## Informations requises :
> Pour que le panel fonction correctement il vous faudra indiquer quelque information sur la base de données.
```php
$Hostname = ""; //Adresse de votre serveur MYSQL qui contient la base de données Authme.
$DbName = ""; //Le nom que vous avez donné à la base de données (par défaut Authme).
$Username = ""; //Le compte utilisateur de la base de données Auhtme (Totale permission sur la base de donnée).
$PassWord = ""; //Mot de passe du compte utilisateur.
```

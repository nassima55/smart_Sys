Employeemanagerapp
Ce projet s’inscrit dans le cadre d’une architecture en deux parties :

Backend : développé avec Spring Boot, il expose des services REST.

Frontend : développé avec Angular, il permet à l’utilisateur d’interagir avec l’application via une interface web.

Serveur de développement (Frontend)
Utilisez la commande ng serve pour lancer le serveur de développement Angular. Ensuite, ouvrez votre navigateur à l'adresse http://localhost:4200/.
L'application se rechargera automatiquement si vous modifiez les fichiers sources.

Génération de composants
Vous pouvez générer un nouveau composant avec la commande ng generate component nom-du-composant.
Il est également possible de générer d’autres éléments comme des directives, des services, des classes, des modules, etc.

Compilation du projet
La commande ng build permet de compiler le projet Angular.
Les fichiers générés seront stockés dans le répertoire dist/.
Pour une version optimisée en production, ajoutez l’option --prod.

Tests unitaires
Lancez les tests unitaires avec la commande ng test.
Les tests seront exécutés via l’outil Karma.

Tests end-to-end
Utilisez la commande ng e2e pour exécuter les tests end-to-end à l’aide de Protractor.

Aide supplémentaire
Pour obtenir plus d'informations sur les commandes Angular CLI, tapez ng help dans le terminal.

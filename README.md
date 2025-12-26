TP 0 ICT301 - KENMOGNE Ange Glorieuse
Matricule : 23U2490

Compréhension des Principes SOLID

1. Single Responsibility Principle (SRP)

    Une classe ne doit avoir qu'une seule et unique responsabilité.

Elle ne doit avoir qu'une seule raison de changer.

Cela permet de réduire le couplage et de faciliter les tests unitaires.

2. Open/Closed Principle (OCP)

    Les entités logicielles (classes, modules, fonctions) doivent être ouvertes à l'extension, mais fermées à la modification.

On doit pouvoir ajouter de nouvelles fonctionnalités sans modifier le code source existant, souvent en utilisant l'héritage ou les interfaces.

3. Liskov Substitution Principle (LSP)

    Les objets d'un programme doivent être remplaçables par des instances de leurs sous-types sans que cela n'altère la cohérence ou la correction du programme.

Une classe dérivée doit pouvoir se substituer à sa classe de base sans changer le comportement attendu.

4. Interface Segregation Principle (ISP)

    Aucun client (classe) ne devrait être forcé de dépendre de méthodes qu'il n'utilise pas.

Il est préférable de créer plusieurs petites interfaces spécifiques plutôt qu'une seule interface générale "grasse".

5. Dependency Inversion Principle (DIP)

    Il faut dépendre des abstractions (interfaces ou classes abstraites) et non des implémentations concrètes.

Les modules de haut niveau ne doivent pas dépendre des modules de bas niveau ; les deux doivent dépendre d'abstractions
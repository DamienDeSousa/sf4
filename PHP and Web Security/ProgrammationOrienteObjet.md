# Programmation orienté objet  
Dans cette partie, les informations trouvées sont disponible [ici](https://fr.wikipedia.org/wiki/SOLID_(informatique)), [ici](), [ici]()

**Questions:**  
1) Quelle est l'idée portée par le S de l'acronyme SOLID ?
2) Quelle est l'idée portée par le O de l'acronyme SOLID ?
3) Qu'est-ce que la contravariance des arguments d'une méthode ?
4) Qu'est-ce que la covariance du type de retour d'une méthode ?
5) Quelle est l'idée portée par le I de l'acronyme SOLID ?
6) Quelle est l'idée portée par le D de l'acronyme SOLID ?

**Questions sans réponses:**  
1) Que veut dire "les préconditions ne peuvent pas être renforcées dans une sous-classe" dans le principe de substitution de Liskov ?
2) Que veut dire "les postconditions ne peuvent pas être affaiblies dans une sous-classe" dans le principe de substitution de Liskov ?

**Réponses:**  
1) Une classe, fonction ou méthode doit avoir une et une seule responsabilité.
2) Une classe doit être ouverte à l'extension mais fermée à la modification.
3) Une méthode qui accepte en argument un type T accepte un type Y si Y est un sur-type de T. [exemple ici](https://en.wikipedia.org/wiki/Covariance_and_contravariance_(computer_science)#Contravariant_method_parameter_type)
4) Une méthode qui retour un type T peut retourner un sous-type de T. [exemple ici](https://en.wikipedia.org/wiki/Covariance_and_contravariance_(computer_science)#Covariant_method_return_type)
5) Préférer plusieurs interfaces spécifiques plutôt qu'une seule générale.
6) Il faut dépendre des abstractions (interfaces, classes abstraites) plutôt que des implémentations (classes concrètes).
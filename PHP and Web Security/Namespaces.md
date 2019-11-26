# Namespaces

Dans cette partie, les informations trouvées sont disponible [ici](https://www.php.net/manual/fr/language.namespaces.php).

**Questions:**

1) Les namespaces sont-ils sensibles à la casse ?
2) Quel est le namespace réservé au langage ?
3) Quels sont les 5 types de code affectés par les namespaces ?
4) A quel endroit sont déclarés les namespaces ?
5) Quel est le seul mot-clé définit avant un namespace ?
6) Est-il possible de définir plusieurs namespace dans un même fichier ?
7) Est-il possible de définir des namespaces sans nom ?
8) Quelles sont les 3 manières possible pour faire référence à une classe ?
9) Quelle constante détermine le namespace dynamiquement ?
10) Quel préfixe est utilisé pour faire appel à l'espace de nom global ?
11) Comment est résolu le nom d'une classe sans namespace ?
12) Dans quel ordre de priorité sont résolues les fonctions et constantes ?

**Réponses:**

1) Oui
2) PHP\ et tous ses sous-namespaces
3) classes (abstraites et finale inclus), traits, interfaces, fonctions, constantes
4) En début de fichier
5) declare, pour plus d'informations, rdv [ici](https://www.php.net/manual/fr/control-structures.declare.php).
6) Oui
7) Oui
8) Un nom de classe sans qualificatif, un nom qualifié et un nom global
9) \_\_NAMESPACE\_\_
10) \
11) PHP va chercher dans le namespace courant la classe en question. Si elle n'y est pas, une erreur est levée.
12) PHP va d'abord chercher dans le namespace courant, puis dans le namespace global.


**Problème de compréhension**

https://www.php.net/manual/fr/language.namespaces.rules.php

Autoload des classes references  
Autoload des méthodes statiques et fonctions
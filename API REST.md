REST (Representational State Transfer) ou RESTful est un style d’architecture permettant de construire des applications (Web, Intranet, Web Service). Il s’agit d’un ensemble de conventions et de bonnes pratiques à respecter et non d’une technologie à part entière. L’architecture REST utilise les spécifications originelles du protocole HTTP, plutôt que de réinventer une surcouche (comme le font SOAP ou XML-RPC par exemple).

* Règle n°1 : l’URI comme identifiant des ressources
  * http://mywebsite.com/books
  * http://mywebsite.com/books?fitlre=policier&tri=asc
  * http://mywebsite.com/books/87
  * http://mywebsite.com/books/87/comments
* Règle n°2 : les verbes HTTP comme identifiant des opérations 
  * Créer (create) => POST
  * Afficher (read) => GET
  * Mettre à jour (update) => PUT
  * Supprimer (delete) => DELETE
* Règle n°3 : les réponses HTTP comme représentation des ressources
  * Accept: application/json
* Règle n°4 : les liens comme relation entre ressources
  Pour expliciter cette description et indiquer la nature de la relation, l’attribut rel doit être spécifier sur tous les liens. Ainsi l’IANA donne une liste de relation parmi lesquelles :
  * contents
  * edit
  * next
  * last
  * payment
* Règle n°5 : un paramètre comme jeton d’authentification

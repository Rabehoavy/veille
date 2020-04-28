JSON Web Tokens permet d’échanger du contenu pour un utilisateur authentifié grâce à la clé secrète utilisée dans la signature. La signature permet également d’assurer l’intégrité du contenu.
Un token JWT se compose de 3 chaines de caractères séparées par un ".".

>eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.
>eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiYWRtaW4iOnRydWV9.
>TJVA95OrM7E2cBab30RMHrHDcEfxjoYZgeFONFh7HgQ

* La première partie, **l'en-tête**, est un JSON encodé en base64 qui décrit le type de token et l'algorithme utilisé pour la signature.
>*Exemple : { "typ": "JWT", "alg": "HS256" } ⇒ eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9 (en base64)*
* La seconde partie, **le payload**, est aussi un JSON encodé en base64 qui contient les informations à transmettre. Ce JSON peut contenir des clefs prédéfinies (appellées claims) qui permettent de donner des informations supplémentaires sur le token (comme la date d'expiration, la cible, le sujet...)
>Quelques **"registered claims"** : **iss** : Origine du token (issuer), **sub** : Sujet (subject), **exp** : Date d’expiration du token (expiration), **iat** : Date de création du token (issued at),

>*Exemple : { "iss": "ekino.com", "name": "John Doe", "admin": true } ⇒ eyAiaXNzIjogImVraW5vLmNvbSIsICJuYW1lIjogIkpvaG4gRG9lIiwgImFkbWluIjogdHJ1ZSB9 (en base64)*
* La dernière partie, **la signature**, est la partie la plus importante du token JWT car elle permet de s'assurer de l'authenticité du token. Cette signature est générée à partir des 2 premières clefs avec un algorithme particulier (HS256 par exemple avec une clef secrète).
>*Exemple : HMACSHA256(eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9 + "." + eyAiaXNzIjogImVraW5vLmNvbSIsICJuYW1lIjogIkpvaG4gRG9lIiwgImFkbWluIjogdHJ1ZSB9,"secret key")*

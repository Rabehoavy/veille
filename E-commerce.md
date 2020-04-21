# [Alternatives à PayPal](https://ecommerce-platforms.com/fr/articles/paypal-alternatives)
* Payline
* Shopify Paiements
* TransferWise
* De forme carré ;
* 2Checkout
* Payoneer
* Skrill
* Stripe
* Google Pay
* Authorize.Net
* Intuit
* Dwolla
* Braintree
* WorldPay
* Amazon Pay
* Klarna
* WePay

Solution |	Frais |	Paiement |	Avantages	 | Inconvénients
------------ | ------------- | ------------- | ------------- | -------------
Paylib | Proposition tarifaire à demander pour les commerçants |	Carte bancaire |	Protection des données : les coordonnées bancaires restent dans votre banque, informations non communiquées à des tiers, protection du consommateur |	Proposé par peu de sites marchands
Stripe |	Pour les start-ups : 1,4% + 0,25 € par transaction avec une carte européenne, 2,9% + 0,25 € avec une carte non européenne. Pour les moyennes et grandes entreprises, tarifs à solliciter au service |	Carte de crédit, AliPay, Android Pay, Apple Pay, Bitcoin, ACH |	Certifié PCI niveau 1 |	Partie de Stripe en anglais
Masterpass |	Gratuit pour les consommateurs, frais à prévoir pour les commerçants |	Carte de crédit |	Haut niveau de sécurité |	Seulement accessible avec carte de crédit
Amazon Pay |	Pour les commerçants, env. 1,9 % et 35 centimes par transaction |	Carte de crédit, prélèvement bancaire |	Pas de compte à créer chez le commerçant, aucune transmission des données bancaires à des tiers |	Ne peut être utilisé qu’avec un compte Amazon, réserves sur la protection des consommateurs
Apple Pay |	Frais pour l’utilisateur non connus, pour les boutiques env. 0,15 % par transaction |	Carte de crédit |	Haut niveau de sécurité |	Uniquement utilisable avec les produits Apple
Google Pay |	Aucun |	Carte de crédit |	Haut niveau de sécurité, peut être utilisé comme une application séparée indépendante de Google |	Déploiement prévu fin 2018
Yesbycash |	Frais de service pour la boutique en ligne |	Espèces |	Permet d’élargir sa cible, nombreux points de vente |	Nécessité de se déplacer à un point de paiement
Skrill |	Aucun |	Carte de crédit, compte courant |	 Maîtrise de ses dépenses grâce au système de carte prépayée, aucune transmission des coordonnées bancaires aux sites marchands |	Service peu utilisé, annulation impossible, frais supplémentaires pour les services complémentaires
Paypal |	30 $ / mois - Paiements Pro, 2,9% + 0,30 $ / transaction, 1-4% / transaction - conversion de devise, 20 $ par rétrofacturation |	Paypal, Visa, Mastercard, AMEX et autres |	202+ pays. Ruby, Python, PHP, Node.js, Java, iOS, Android |
Braintree |	Pas de frais mensuels, 2,9% + 0,30 $ / transaction, 1% / transaction - conversion de devise, 15 $ / rejet de débit |	PayPal, Venmo, Android Pay, Apple Pay, Bitcoin, Visa, MasterCard, AMEX et autres |	46 pays. Ruby, Python, PHP, Node.js, Java, Android, iOS |	 

# Sandbox
Le Sandbox désigne le fait qu’un programme soit mis de côté par d’autres programmes dans un environnement séparé. Ainsi, en cas d’erreur ou de problème de sécurité, ces problèmes ne se propagent pas dans d’autres zones de l’ordinateur. Les programmes sont activés dans leur propre zone séquestrée, où ils peuvent être travaillés sans poser de menace pour les autres programmes. Les bacs à sable sont donc utilisés pour exécuter en toute sécurité un code suspect sans que le périphérique hôte ou le réseau ne soit endommagé.

# Payement process
Entreprise autorisée à traiter les transactions par carte de crédit entre vendeurs et acheteurs. Le processeur de paiement est souvent la tierce partie et sera nommé par le commerçant. Il existe deux types de processeurs de paiement. extrémité avant et arrière.

Un processeur frontal sera connecté à diverses associations de cartes et fournira des services de règlement et une autorisation aux commerçants des banques d'affaires. Les processeurs dorsaux sont utilisés pour accepter les règlements des processeurs frontaux et pour transférer de l'argent de la banque émettrice vers la banque d'affaires, ce processus étant achevé en quelques secondes.

Ces processeurs exécutent de nombreuses fonctions, telles que l’évaluation de la validité et de l’approbation des transactions, en utilisant des mesures anti-fraude pour s’assurer qu’une transaction d’achat est initiée par la source qu’elle prétend être. Les processeurs sont tenus de respecter les normes et réglementations organisées par les associations de cartes de crédit. Ces normes incluent des règles concernant la fraude, les rétrofacturations et le vol d'identité.

# Obligations légales
* Recueillir l'accord des clients
* Informer les clients de leur droit d'accès, de modification et de suppression des informations collectées
* Veiller à la sécurité des systèmes d'information et la confidentialité des données
* Assurer la confidentialité des données
* Indiquer une durée de conservation des données

# Conditions Générales des Ventes (CGV)
* Champ d’application et objet
* Présentation des produits
* Prix (en euros TTC) 
* Durée de validité des offres
* Processus de commande
* Frais et date de livraison 
* Modalités de paiement 
* Retards de paiement (notamment pénalités de retard et indemnité de recouvrement)
* Services après-vente 
* Droit de rétractation 
* Coût de la communication à distance (frais téléphonique).

# Paypal IPN
La notification de paiement instantanée (IPN) est un service de messagerie qui informe automatiquement les commerçants des événements liés aux transactions PayPal. Les commerçants peuvent l'utiliser pour automatiser les fonctions administratives et de back-office, notamment pour exécuter automatiquement les commandes et fournir aux clients le statut des commandes.
* Paiements reçus, y compris Paiement express et Paiements adaptatifs.
* Autorisations de carte de crédit.
* Paiements eCheck et événements associés en cours, terminés ou refusés.
* Paiements récurrents et actions d'abonnement.
* Remboursements, litiges, annulations et remboursements.

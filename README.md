# ecommerce-django-Javascript

J'ai créé un site e-commerce en utilisant Django pour le backend et HTML, CSS, et JavaScript pour le frontend. Au sein du projet Django, j'ai organisé mon code dans une application nommée 'store'. La page principale, 'main.html', sert d'interface principale pour le site. De plus, j'ai créé trois pages distinctes : 'store.html', 'checkout.html' et 'cart.html'.


De plus, pour représenter la structure globale et le flux du site web, j'ai créé un diagramme de classes. Ce diagramme illustre les relations entre les différentes classes et aide à visualiser comment les données circulent dans le système.


Pour gérer les données de l'application, j'ai conçu une base de données en utilisant les modèles Django. J'ai défini cinq classes dans le fichier models.py :

Customer : Représente les informations sur les clients.
Product : Représente les produits disponibles à l'achat.
Order : Capture les détails sur les commandes passées par les clients.
OrderItem : Représente les articles individuels au sein d'une commande.
ShippingAddress : Stocke les informations d'expédition liées à une commande.


Dans le fichier views.py, j'ai implémenté des fonctions pour gérer la logique de l'application. Ces fonctions facilitent des actions telles que l'affichage des produits sur la page du magasin, la gestion du panier d'achat, le traitement des commandes lors du paiement, et la gestion des informations d'expédition.

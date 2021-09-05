# GLS Magento 2 Changelog

## 1.1.2 (27/04/2021)

### Correctifs
- Lors de l'import des numéros de tracking, dans le mail envoyé au client, le lien de tracking pouvait rediriger sur une page qui n'existait pas
- L'affichage de l'option "URL de suivi" dans la configuration dépendait de l'activation de la méthode de livraison en point relais
- Si uniquement les méthodes GLS sont activées, le tunnel de commande pouvait ne pas lancer la rechercher des méthodes de livraison quand on saisisait l'adresse de livraison
- Lors de l'export, les champs pouvait se décaler a partir de l'adresse.
- Nous avions une incidence sur l'ordre du menu "Shipping methods" dans "Sales" dans la configuration Magento
- Sur le listing des commandes pour l'export, un problème pouvait se poser sur le filtre de date a partir de la version 2.3.4 de Magento
- Lors du téléchargement des commandes à exporter, certains caractères sépciaux pouvait poser un problème
- Le téléchargement en masse pouvait ne pas fonctionner

## 1.1.1

### Correctifs
- La carte Google Maps pour le choix d'un point relais pouvait ne pas s'afficher tout de suite
- L'option "URL de suivi" dans la configuration ne dépend plus de l'activation de la livraison en point relais
- Lorsque les méthodes de livraison GLS sont les seules activées sur le site, elle pouvait ne pas s'afficher correctement
- Utilisation des bonnes version d'Owebia  

## 1.1

### Améliorations
- Ajout de la pagination sur la page Export
- Ajout de la compatibilité avec Magento 2.3
- Ajout de la compatibilité avec la version 2.6.X de Owebia Advanced Setting Core
- Ajout de la compatibilité avec la version 2.6.X de Owebia Advanced Shipping 


### Correctifs
- Corrections d'un bug à l'export des commandes pouvant causer des erreurs dans l'adresse de livraison

# Cartographie de cadrage du projet - Leboncoin

## Projet

**Nom :** Leboncoin

**Description :**
Plateforme de petites annonces permettant aux particuliers et professionnels de vendre, acheter et échanger des biens et services.

---

## Unité fonctionnelle

Permettre la mise en relation entre un acheteur et un vendeur via la consultation et la publication d'annonces.

---

## Contraintes identifiées

### Technique

* Plusieurs millions d'annonces contenant des images et des données à afficher.
* Nécessité de garantir des temps de chargement rapides malgré un fort trafic.
* Compatibilité avec de nombreux navigateurs, appareils et versions mobiles.
* Présence d'anciens composants techniques nécessitant une maintenance continue.

### Organisation

* Multiples équipes produit, design, frontend, backend et infrastructure.
* Coordination complexe entre les différents métiers.
* Déploiements fréquents nécessitant une validation rigoureuse.

### Budget

* Coût important lié au stockage des images et des données.
* Consommation élevée des ressources serveurs et CDN.
* Nécessité d'optimiser les coûts d'infrastructure à grande échelle.

### Humain

* Habitudes utilisateurs fortement ancrées.
* Risque de dégrader l'expérience utilisateur lors de changements d'interface.
* Besoin de sensibiliser les équipes aux enjeux d'éco-conception dans un contexte de forte croissance.

---

## Parties prenantes

### Acheteurs

* Recherchent et consultent des annonces.
* Contactent les vendeurs.

### Vendeurs

* Publient des annonces.
* Téléchargent des photos.
* Gèrent leurs messages.

### Équipes Produit

* Définissent les évolutions fonctionnelles.

### Équipes Techniques

* Développent et maintiennent la plateforme.

### Infrastructure

* Gère les serveurs, bases de données, CDN et stockage.

---

## Anti-patterns identifiés

* Images trop lourdes.
* Chargement excessif des résultats de recherche.
* Scroll infini générant des téléchargements inutiles.
* Conservation de données et messages obsolètes.
* Notifications non essentielles.

---

## Objectifs d'éco-conception

* Réduire le poids des images grâce aux formats WebP/AVIF.
* Mettre en place le Lazy Loading sur les listes d'annonces.
* Adapter les images à la taille réelle d'affichage.
* Remplacer le scroll infini par un chargement à la demande.
* Réduire les notifications inutiles.
* Purger automatiquement les données anciennes.

---

## Critères de réussite

* Réduction du poids moyen des pages.
* Diminution du trafic réseau généré par utilisateur.
* Réduction du stockage occupé par les données obsolètes.
* Amélioration du score EcoIndex.
* Maintien de la satisfaction utilisateur malgré les optimisations.

# Backlog heavy-hub

## Contexte du projet

Le projet represente un portail membre avec home connectee, bibliotheque, detail contenu, dashboard, notifications et profil.
# User Stories - Heavy-Hub

## User story 1

* Contexte: En tant qu'utilisateur, je veux que les images de l'espace membre soient compressées afin de réduire le temps de chargement des pages.
* Objectif: Réduire de 50 % le poids moyen des images.
* Bonne pratique d'eco-conception ciblee: Compression et formats modernes d'images (WebP/AVIF).
* KPI associe: Poids moyen des images (Ko).
* Repo ou ecran concerne: Galerie photos et espace membre.
* Critere de reussite: 100 % des nouvelles images sont servies en WebP ou AVIF.
* Niveau de priorite: Haute.

## User story 2

* Contexte: En tant qu'utilisateur, je veux que seules les images visibles soient chargées afin d'économiser mes données mobiles.
* Objectif: Réduire le volume de données téléchargées au chargement initial.
* Bonne pratique d'eco-conception ciblee: Mise en place du Lazy Loading.
* KPI associe: Nombre d'images chargées au premier affichage.
* Repo ou ecran concerne: Liste des publications et espace membre.
* Critere de reussite: Les images hors écran ne sont chargées qu'au défilement.
* Niveau de priorite: Haute.

## User story 3

* Contexte: En tant qu'utilisateur, je veux que mon avatar soit affiché à la taille adaptée afin d'éviter les téléchargements inutiles.
* Objectif: Réduire le poids des avatars affichés sur les pages.
* Bonne pratique d'eco-conception ciblee: Servir des images à la taille exacte d'affichage.
* KPI associe: Taille moyenne des avatars téléchargés.
* Repo ou ecran concerne: Profil utilisateur, commentaires et messagerie.
* Critere de reussite: Aucun avatar n'est téléchargé dans une résolution supérieure à celle affichée.
* Niveau de priorite: Haute.

## User story 4

* Contexte: En tant qu'utilisateur, je veux afficher davantage de contenus uniquement lorsque je le décide afin de garder le contrôle sur ma navigation.
* Objectif: Réduire le nombre de contenus chargés automatiquement.
* Bonne pratique d'eco-conception ciblee: Remplacer le scroll infini par un bouton "Voir plus".
* KPI associe: Nombre d'éléments chargés automatiquement.
* Repo ou ecran concerne: Fil d'actualité et résultats de recherche.
* Critere de reussite: Le chargement de contenu supplémentaire nécessite une action volontaire de l'utilisateur.
* Niveau de priorite: Moyenne.

## User story 5

* Contexte: En tant qu'utilisateur, je veux recevoir uniquement les notifications importantes afin d'éviter les sollicitations inutiles.
* Objectif: Réduire le volume de notifications envoyées.
* Bonne pratique d'eco-conception ciblee: Réduction des notifications bavardes.
* KPI associe: Nombre moyen de notifications envoyées par utilisateur.
* Repo ou ecran concerne: Centre de notifications et emails automatiques.
* Critere de reussite: Diminution d'au moins 30 % des notifications non essentielles.
* Niveau de priorite: Moyenne.

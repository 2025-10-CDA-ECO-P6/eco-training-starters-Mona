# Backlog heavy-hub - YOUTUBE

## Contexte du projet
Le projet represente un portail membre avec home connectee, bibliotheque, detail contenu, dashboard, notifications et profil.

## User story 1

- **Contexte** : En tant que responsable produit YouTube, je veux adapter automatiquement la qualité des vidéos aux conditions de connexion afin de limiter les transferts de données inutiles tout en conservant une bonne expérience utilisateur.
- **Objectif** : Réduire le volume de données transférées lors de la lecture d'une vidéo.
- **Bonne pratique d'eco-conception ciblee** : Adapter la qualité des médias au contexte d'utilisation.
- **KPI associe** : Taille des données téléchargées (Ko/Mo).
- **Repo ou ecran concerne** : Ecran de lecture vidéo.
- **Critere de reussite** : Diminution d'au moins 20 % du volume moyen de données téléchargées.
- **Niveau de priorite** : Haute

## User story 2

- **Contexte** : En tant que responsable produit YouTube, je veux limiter le chargement automatique des contenus non consultés afin de réduire les requêtes inutiles et la consommation de ressources.
- **Objectif** : Réduire les transferts réseau inutiles.
- **Bonne pratique d'eco-conception ciblee** : Mettre en place un chargement à la demande (lazy loading).
- **KPI associe** : Nombre de requêtes réseau.
- **Repo ou ecran concerne** : Page d'accueil, recommandations et lecture vidéo.
- **Critere de reussite** : Réduction d'au moins 15 % du nombre moyen de requêtes générées lors d'une session utilisateur.
- **Niveau de priorite** : Haute

## User story 3

- **Contexte** : En tant que responsable produit YouTube, je veux optimiser le poids des vidéos diffusées afin de réduire la bande passante consommée et l'impact environnemental du service.
- **Objectif** : Réduire le poids des contenus vidéo.
- **Bonne pratique d'eco-conception ciblee** : Optimiser et compresser les médias diffusés.
- **KPI associe** : Taille moyenne des ressources téléchargées.
- **Repo ou ecran concerne** : Plateforme de diffusion vidéo.
- **Critere de reussite** : Réduction d'au moins 20 % du poids moyen des vidéos diffusées sans dégradation significative de la qualité perçue.
- **Niveau de priorite** : Haute
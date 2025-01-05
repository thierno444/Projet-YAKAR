# Projet YAKAR

## Description du projet
La structure de transformation des produits locaux "YAKAR" souhaite contrôler la température et l'humidité de son magasin de stockage via une interface web. Le système doit permettre :

1. **Détection et affichage** :
   - Température et humidité détectées en temps réel via une interface web et un écran LCD.
   - Déclenchement automatique d'un buzzer, de la ventilation, et d'un signal rouge si la température dépasse 27°C.
   - Signal vert activé et ventilateur éteint lorsque la température est normale (≤ 27°C).
   - Activation manuelle du ventilateur via une télécommande ou l'interface web.

2. **Collecte des données** :
   - Température et humidité mesurées trois fois par jour aux heures suivantes : 10h00, 14h00, et 17h00.
   - Données stockées dans une base de données à chaque collecte.

3. **Dynamisme des images** :
   - Changement d'images en fonction des valeurs d'humidité (ex : si l'humidité dépasse une valeur seuil).

## Fonctionnalités

### Utilisateur simple
- Consultation en temps réel de la température et de l'humidité.
- Consultation des relevés pour chaque heure donnée.
- Consultation de la température et de l'humidité moyennes de la journée.

### Administrateur
- Contrôle du système via un tableau de bord (allumer/éteindre le ventilateur).
- Gestion des utilisateurs (création de comptes, modification d'accès, suppression, changement de rôle).
- Accès à l'historique des températures de la semaine.

## Compétences visées
- Utilisation des outils collaboratifs.
- Gestion de projet avec la méthode Agile.
- Création de mindmaps, maquettes et mockups.
- Câblage de circuits avec microcontrôleurs.
- Développement front-end et back-end.
- Création et gestion de bases de données.

## Outils et langages utilisés
- Microcontrôleur et capteurs (température, humidité).
- Node.js, Express, WebSocket.
- MongoDB pour la base de données.

## Résultats attendus
- Travail en équipe avec un outil collaboratif (ex: Trello).
- Contributions régulières sur un dépôt Git (GitHub, GitLab, ou Bitbucket).
- Développement complet :
  - Front-end.
  - Back-end.
  - Composants d'accès à une base de données.
- Documentation complète de l'application.
- Présentation finale (PowerPoint).

## Livrables
- Mindmap et maquette de l'application.
- Tableau Trello pour la gestion de projet.
- Circuit correctement câblé.
- Code source sur un dépôt Git.
- Documentation technique et utilisateur.
- Présentation PowerPoint.

## Délai
Le projet doit être finalisé dans un délai de **10 jours** à compter de la date de démarrage.

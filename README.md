# Présentation du projet

---

## **Contexte et objectifs**

Le projet Assistant LuDé vise à créer un assistant sur une plateforme Web Application dédiée à la communauté Ludisep, conçu pour centraliser et faciliter l’organisation d’événements tels que la Nuit Ludisep. L’outil propose une expérience en ligne ou application autour de quatre fonctionnalités principales :

- Recommandation personnalisée de jeux de société grâce à un algorithme adapté aux préférences des utilisateurs.
- Réservation de salles avec gestion des créneaux horaires et des disponibilités.
- Inscription à des événements, notamment la Nuit Ludisep, pour simplifier la participation.
- Tableau de bord interactif pour visualiser les sessions, les salles réservées, les participants et le planning en temps réel.

Les objectifs principaux sont de centraliser la gestion des événements, de faciliter l’organisation pour les membres et d’accroître la visibilité de la communauté.

---

## **Spécifications techniques**

Le développement du projet s’appuie sur les technologies suivantes :

- **Langages de programmation** :
    - Frontend : **Framework React**
    - Backend : **Python** avec le **Framework Django**
- **Base de Données** :
    - **PostgreSQL**
- Intégration d’un module de notifications (push ou email) pour tenir informés les utilisateurs.
    - **SendGrid**, **Mailgun** (envoie de mail avec intégration facile a **Python**)
- Accès facilité à la base de données des jeux pour une gestion rapide et efficace.
- Outils permettant la modification rapide du thème graphique et de la base de données.

---

## **Outils de Développement et Gestion de Projet**

- **Contrôle de version et de partage** : Utilisation de la plateforme **Github**
- **Gestion des taches** : Trello
- **Environnement de développement** : Visual Studio Code

---

## Planification initiale (Roadmap)

Découpe du projet en plusieurs petit version viable **Minimum Viable Product** (MVP).

### Phase 1 : Minimum Viable Product (MVP)

### Sous-Phase 1.1 : Initialisation et Configuration de Base

**Objectif** : Configurer l'environnement de développement et créer les structures de base de l'application.

**Fonctionnalités** :

- **Configuration de l'environnement** :
    - Installation et configuration de Django et React.
    - Configuration de la base de données PostgreSQL.
- **Création des modèles de base** :
    - Modèles pour les utilisateurs, les jeux, les salles et les événements.
- **Interface utilisateur basique** :
    - Page d'accueil avec navigation de base.
    - Pages de connexion et d'inscription.

**Livrables** :

- Environnement de développement configuré.
- Modèles de base créés.
- Interface utilisateur basique fonctionnelle.

**Durée estimée** : 1 mois

### Sous-Phase 1.2 : Recommandation de Jeux

**Objectif** : Implémenter la fonctionnalité de recommandation de jeux.

**Fonctionnalités** :

- **Questionnaire de préférences** :
    - Formulaire pour recueillir les préférences des utilisateurs (durée de jeu, nombre de joueurs, thème).
- **Algorithme de recommandation** :
    - Algorithme simple pour filtrer les jeux en fonction des préférences.
- **Affichage des recommandations** :
    - Page pour afficher les jeux recommandés.

**Livrables** :

- Questionnaire de préférences fonctionnel.
- Algorithme de recommandation implémenté.
- Page de recommandations fonctionnelle.

**Durée estimée** : 1 mois

### Sous-Phase 1.3 : Réservation de Salles

**Objectif** : Implémenter la fonctionnalité de réservation de salles.

**Fonctionnalités** :

- **Interface de réservation** :
    - Page pour sélectionner et réserver des salles.
- **Gestion des créneaux horaires** :
    - Système pour vérifier la disponibilité des salles.
- **Confirmation de réservation** :
    - Page de confirmation et notification par email.

**Livrables** :

- Interface de réservation fonctionnelle.
- Système de gestion des créneaux horaires implémenté.
- Page de confirmation et notifications par email.

**Durée estimée** : 1 mois

### Sous-Phase 1.4 : Inscription à des Événements

**Objectif** : Implémenter la fonctionnalité d'inscription à des événements.

**Fonctionnalités** :

- **Interface d'inscription** :
    - Page pour s'inscrire à la Nuit Ludisep et à des sessions de jeu.
- **Gestion des inscriptions** :
    - Système pour vérifier la disponibilité et confirmer les inscriptions.
- **Confirmation d'inscription** :
    - Page de confirmation et notification par email.

**Livrables** :

- Interface d'inscription fonctionnelle.
- Système de gestion des inscriptions implémenté.
- Page de confirmation et notifications par email.

**Durée estimée** : 1 mois

### Sous-Phase 1.5 : Tableau de Bord

**Objectif** : Implémenter le tableau de bord interactif.

**Fonctionnalités** :

- **Visualisation des sessions** :
    - Page pour visualiser les sessions et les salles réservées.
- **Statistiques de participation** :
    - Graphiques et visualisations en temps réel.

**Livrables** :

- Tableau de bord interactif fonctionnel.
- Visualisations et statistiques en temps réel.

**Durée estimée** : 1 mois

### Phase 2 : Améliorations et Fonctionnalités Avancées

### Sous-Phase 2.1 : Amélioration de la Recommandation de Jeux

**Objectif** : Améliorer l'algorithme de recommandation de jeux.

**Fonctionnalités** :

- **Critères détaillés** :
    - Ajout de critères supplémentaires pour le questionnaire de préférences.
- **Commentaires et notes** :
    - Intégration de commentaires et de notes des utilisateurs.

**Livrables** :

- Algorithme de recommandation amélioré.
- Intégration des commentaires et des notes.

**Durée estimée** : 1 mois

### Sous-Phase 2.2 : Amélioration de la Réservation de Salles

**Objectif** : Améliorer la fonctionnalité de réservation de salles.

**Fonctionnalités** :

- **Notifications avancées** :
    - Notifications par email pour les réservations et annulations.
- **Gestion des annulations** :
    - Système pour gérer les annulations et les modifications de réservation.

**Livrables** :

- Notifications avancées implémentées.
- Système de gestion des annulations.

**Durée estimée** : 1 mois

### Sous-Phase 2.3 : Amélioration de l'Inscription à des Événements

**Objectif** : Améliorer la fonctionnalité d'inscription à des événements.

**Fonctionnalités** :

- **Paiements en ligne** :
    - Intégration de paiements en ligne pour les événements payants.
- **Listes d'attente** :
    - Gestion des listes d'attente pour les événements complets.

**Livrables** :

- Paiements en ligne intégrés.
- Gestion des listes d'attente.

**Durée estimée** : 1 mois

### Sous-Phase 2.4 : Amélioration du Tableau de Bord

**Objectif** : Améliorer le tableau de bord interactif.

**Fonctionnalités** :

- **Graphiques avancés** :
    - Ajout de graphiques et de visualisations avancées.
- **Export des données** :
    - Export des données en format CSV ou PDF.

**Livrables** :

- Graphiques et visualisations avancées.
- Fonctionnalité d'export des données.

**Durée estimée** : 1 mois

### Phase 3 : Optimisation et Déploiement

**Objectif** : Optimiser l'application pour la performance et la scalabilité, et préparer le déploiement.

**Fonctionnalités** :

- **Optimisation des performances** :
    - Optimisation de la base de données et des requêtes.
    - Mise en cache des données fréquemment utilisées.
- **Sécurité** :
    - Implémentation de mesures de sécurité avancées (authentification à deux facteurs, chiffrement des données).
    - Tests de pénétration et audits de sécurité.
- **Déploiement** :
    - Configuration de l'infrastructure de production.
    - Mise en place de sauvegardes automatiques et de plans de reprise après sinistre.

**Livrables** :

- Application web optimisée et sécurisée.
- Documentation complète pour le déploiement et la maintenance.
- Plan de déploiement et de support.

**Durée estimée** : 1 mois

---

## Infrastructure de développement

### Matériel

- **Raspberry Pi 4 Model B** (4GB)
- **SSD Externe via USB 3.0** : Pour le système d'exploitation, l'application et la base de données
- **Alimentation électrique** : Bonne qualité pour éviter les coupures
- **Boîtier avec refroidissement** : Passif ou actif pour éviter la surchauffe

### Logiciel

- **OS** : Raspberry Pi OS Lite (64-bit) sans interface graphique
- **Base de Données** : **PostgreSQL**
- **Serveur Web** : Nginx (comme reverse proxy pour Gunicorn et pour servir les fichiers statiques)
- **Serveur d'Application WSGI** : Gunicorn pour faire tourner l'application Django/Python
- **Gestionnaire de Processus** : `systemd` pour s'assurer que Gunicorn démarre automatiquement et redémarre en cas de crash

### **Sécurité**

- `ufw` : Pare-feu
- `fail2ban` : Pour bloquer les tentatives d'intrusion
- **Certbot** pour Let's Encrypt (HTTPS)
- **Accès Externe** :
    - Service DDNS (ex: No-IP, DuckDNS)
    - Configuration de la redirection de port sur le routeur
- **Sauvegardes** : Stratégie de sauvegarde régulière de la base de données et des fichiers

### Configuration

1. **Installation de l'OS** : Raspberry Pi OS Lite (64-bit)
2. **Configuration du SSD Externe** : Pour le système d'exploitation, l'application et la base de données
3. **Installation des logiciels** : **PostgreSQL**, **Nginx**, **Gunicorn**, `systemd`, `ufw`, `fail2ban`, **Certbot**
4. **Configuration de la sécurité** : Pare-feu, HTTPS, sauvegardes
5. **Configuration de l'accès externe** : Service DDNS, redirection de port

---

## **Architecture fonctionnelle**

Les principaux workflows sont :

- **Recommandation de jeux** : L’utilisateur répond à un questionnaire (durée de jeu, nombre de joueurs, thème préféré), puis l’algorithme filtre la base de données pour proposer des suggestions adaptées.
- **Réservation de salle** : L’utilisateur sélectionne un créneau, le système vérifie la disponibilité, confirme la réservation et peut envoyer une notification par email. La gestion des annulations est également prévue.
- **Visualisation des sessions** : Les utilisateurs peuvent consulter la liste des salles réservées, obtenir des informations sur leurs utilisations et accéder à des statistiques de participations en temps réel.
- **Inscription à une session de jeu** : Sélection de la session, vérification de la disponibilité, confirmation et notification optionnelle par email. Les annulations sont gérées de la même manière.
- **Inscription à la Nuit Ludisep** : Inscription à la nuit Ludisep ce qui débloque la possibilité aux autres inscriptions (session de jeu et réservation de salle).

---

## **Design et expérience utilisateur**

Le design s’inspire de la charte graphique de Ludisep et LuDé, avec une palette colorée et des icônes animés pour renforcer l’identité visuelle. Les maquettes exigées incluent :

- Une page d’accueil présentant les différentes fonctionnalités (réservation, visualisation des salles, etc.).
- Une interface administrateur sécurisée par mot de passe pour la gestion des événements et des utilisateurs inscrits.

---

## U**tilisateurs cibles**

Les utilisateurs type de mon application

- Client de Ludisep
    - Interfaces d’accueil avec fonctionnalité (Recommandation de jeux, Réservation de salle, Visualisions des sessions, Inscriptions à une sessions de jeu et inscription a la nuit Ludisep)
- Admin Ludisep
    - Interfaces d’accueil avec fonctionnalité pour gérer la création ou l’annulation d’évènement ou de session de jeu, pouvoir imprimer la liste des personnes inscrite, gérer les listes personnes inscrites aux différents évènements et gérer les modifications d’évènements.

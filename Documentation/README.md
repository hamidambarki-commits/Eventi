
# 🎉 E-venti — Plateforme de gestion d'événements

## 📌 Présentation

**E-venti** est une plateforme digitale de gestion d'événements qui permet aux utilisateurs de découvrir, réserver et participer à différents événements.

Elle facilite également le travail des organisateurs en leur permettant de créer et gérer leurs événements, leurs réservations et leurs offres.

Le projet repose sur une architecture **microservices**, où chaque service possède une responsabilité spécifique.

---

## 🎯 Objectifs

- Simplifier l'organisation et la gestion des événements.
- Faciliter la réservation et le suivi des participants.
- Améliorer la visibilité des événements.
- Encourager les interactions entre les utilisateurs.
- Faciliter la gestion des sponsors et des offres promotionnelles.
- Proposer une plateforme moderne, évolutive et indépendante grâce aux microservices.

---

## ✨ Fonctionnalités

### 👤 Gestion des utilisateurs
- Inscription et connexion.
- Gestion des comptes.
- Gestion des rôles et des permissions.
- Participants, organisateurs et administrateurs.

### 🎫 Gestion des événements
- Création et publication d'événements.
- Consultation des événements.
- Réservation et suivi des participants.

### 💬 Commentaires
- Ajouter des commentaires.
- Répondre aux commentaires.
- Interagir avec les événements.

### 🤝 Sponsors
- Gestion des sponsors.
- Gestion des sponsorings.
- Suivi du financement des événements.

### 📢 Réclamations
- Déposer une réclamation.
- Consulter et suivre son état.
- Gestion des réponses.

### 🎁 Offres et coupons
- Gestion des offres promotionnelles.
- Création de coupons de réduction.
- Application des coupons.

### 🤖 Intelligence artificielle
- Chatbot intelligent.
- Recommandations personnalisées.

---

## 🏗️ Architecture

E-venti utilise une architecture basée sur des microservices indépendants.

| Microservice | Responsabilité |
|---|---|
| MS1 – Users | Utilisateurs et rôles |
| MS2 – Events | Événements et réservations |
| MS3 – Comments | Commentaires et réponses |
| MS4 – Sponsors | Sponsors et sponsoring |
| MS5 – Complaints | Réclamations et réponses |
| MS6 – Offers | Offres et coupons |
| MS7 – AI | Chatbot et recommandations |

Chaque microservice possède sa propre base de données et communique avec les autres services à travers des API REST ou des événements asynchrones.

---

## 🗄️ Bases de données

| Microservice | Database |
|---|---|
| Users | MySQL |
| Events | MySQL |
| Comments | MongoDB |
| Sponsors | MySQL |
| Complaints | MySQL |
| Offers | MySQL |

---

## ⚙️ Technologies

- Java
- Spring Boot
- Spring Cloud
- REST API
- MySQL
- MongoDB
- Docker
- Eureka
- API Gateway
- Config Server
- Keycloak
- OpenFeign
- Git & GitHub

---

## 🔄 Communication entre services

Les microservices communiquent selon deux méthodes :

- **Communication synchrone :** appels directs entre services via REST et OpenFeign.
- **Communication asynchrone :** événements permettant aux services de communiquer sans dépendance directe.

---

## 🔐 Sécurité

L'authentification et la gestion des rôles sont assurées à travers Keycloak.

La plateforme distingue différents rôles selon les responsabilités des utilisateurs.

---

## 👥 Équipe du projet

- Amal Aouamri
- Chaima Ayari
- Mahdi Belhaj
- Mohamed Omar Bdiri
- Sirine Gizeni
- Hamida Mbarki

---

## 🚀 Installation et lancement

### Prérequis

- Java
- Maven
- Docker
- Git

### Cloner le projet

```bash
git clone YOUR_REPOSITORY_URL
```

### Accéder au projet

```bash
cd E-venti
```

### Lancement

Les instructions de lancement dépendent de la configuration Docker et des microservices du projet.

---

## 📂 Structure du projet

```text
E-venti/
│
├── users-service/
├── events-service/
├── comments-service/
├── sponsors-service/
├── complaints-service/
├── offers-service/
├── ai-service/
│
├── api-gateway/
├── config-server/
├── discovery-server/
│
├── docker-compose.yml
└── README.md
```

---

## 🌱 Objectifs futurs

- Améliorer les recommandations personnalisées.
- Ajouter de nouvelles fonctionnalités intelligentes.
- Optimiser les performances.
- Améliorer l'expérience utilisateur.
- Ajouter de nouvelles intégrations.

---

## 📄 Licence

Projet académique réalisé dans le cadre de nos études à ESPRIT.

---

⭐ **E-venti — Organisez, découvrez et participez aux événements facilement !**

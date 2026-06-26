🌍 Fuel & Carbon Emission Tracking System

📌 Description du projet

Ce projet est une plateforme intelligente de **suivi de consommation de carburant et d’émissions de carbone** pour les compagnies aériennes et les systèmes de transport.

L’application permet de :

* Collecter des données depuis des fichiers **Excel, CSV et PDF**
* Faire du **scraping de données depuis des sites web**
* Calculer les émissions de CO₂ automatiquement
* Fournir des **notifications en temps réel**
* Visualiser les données via un dashboard web
* Assurer une infrastructure **DevOps complète (CI/CD + monitoring + Kubernetes)**

---

 🚀 Fonctionnalités principales

 📊 Data & Analytics

* Import de fichiers (Excel / CSV / PDF)
* Scraping automatique de données de fuel
* Nettoyage et transformation des données
* Calcul des émissions carbone (CO₂)
* Historique des vols et consommation

 🔔 Temps réel

* Notifications en temps réel selon secteur client
* Alertes sur consommation anormale
* Système d’événements live (WebSocket)

 👥 Gestion utilisateurs

* Authentification sécurisée (JWT)
* Rôles utilisateurs :

  * Admin
  * Analyste
  * Opérateur Fuel
  * Responsable environnement

📈 Dashboard

* Statistiques de consommation
* Graphiques d’émissions carbone
* Suivi des vols
* Filtres avancés

---

🏗️ Architecture globale

```
Frontend (React)
        |
        | API REST / WebSocket
        |
Backend (Node.js / Python services)
        |
MongoDB Database
        |
Data Pipeline (Scraping + ETL)
        |
DevOps Layer (Docker + Jenkins + Kubernetes + Monitoring)
```

---

 🧰 Technologies utilisées

Frontend

* ⚛️ React

 Backend

* 🟢 Node.js
* 🐍 Python (scraping + ETL + data processing)

 Base de données

* 🍃 MongoDB

DevOps & Infrastructure

* ☸️ Kubernetes
* 🔧 Jenkins
* 🐳 Docker
* 📊 Monitoring (Prometheus / Grafana)

---

⚙️ Installation & exécution

1️⃣ Cloner le projet

```bash
git clone https://github.com/your-repo/fuel-carbon-tracking.git
cd fuel-carbon-tracking
```

---

2️⃣ Backend (Node.js)

```bash
cd backend
npm install
npm start
```

---

 3️⃣ Frontend (React)

```bash
cd frontend
npm install
npm start
```

---

4️⃣ Service scraping (Python)

```bash
cd scraping
pip install -r requirements.txt
python main.py
```

---

🐳 Docker

```bash
docker-compose up --build
```

---

☸️ Kubernetes Deployment

```bash
kubectl apply -f k8s/
```

Contient :

* Deployment backend
* Deployment frontend
* Service MongoDB
* Ingress controller

---
 🔁 CI/CD Pipeline (Jenkins)

Pipeline Jenkins automatisé :

1. Build du code
2. Tests unitaires
3. Build Docker images
4. Push vers registry
5. Deploy sur Kubernetes

---
📡 Scraping & Data ingestion

Le système collecte automatiquement :

* Données de vols
* Consommation fuel
* Rapports externes
* Fichiers Excel / CSV uploadés

Technologies :

* BeautifulSoup
* Pandas
* OpenPyXL
* Requests

---

🔔 Notifications temps réel

Système basé sur :

* WebSockets
* Event-driven architecture
* Alertes par secteur utilisateur
* Notifications instantanées dashboard

---

📊 Monitoring

* Logs centralisés
* Monitoring cluster Kubernetes
* CPU / RAM usage tracking
* Alerting système (Prometheus + Grafana)

---

📁 Structure du projet

```
project-root/
│
├── backend/
├── frontend/
├── scraping/
├── devops/
│   ├── docker/
│   ├── kubernetes/
│   └── jenkins/
│
├── data/
│   ├── excel/
│   ├── pdf/
│
└── README.md
```

---
 🎯 Objectifs du projet

* Réduire la consommation de carburant
* Optimiser les coûts opérationnels
* Surveiller les émissions carbone
* Automatiser le traitement des données
* Fournir des alertes en temps réel

 🚀 Améliorations futures

* IA pour prédiction de consommation fuel
* Optimisation automatique des routes
* Mobile app (React Native)
* Intégration IoT (capteurs avion)
* Dashboard avancé en temps réel

---

👨‍💻 Auteur

Projet développé dans un contexte académique / professionnel pour la gestion intelligente du fuel et de l’empreinte carbone.
 
 

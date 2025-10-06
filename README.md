# 👋 Salut ! Je suis Abdelilah Benkida — `@abdelilahraees`

![Header image](https://github.com/abdelilahraees/abdelilahraees/raw/main/profile-header-bg.png)

Développeur **Full-Stack** Java / Angular — Étudiant en **Master 2 Ingénierie Informatique**.  
Je conçois des API robustes avec **Spring Boot** et des interfaces réactives avec **Angular**.  
Je cherche des opportunités de stage de fin d'études et des projets open-source où contribuer.

---

### 🚀 À propos (extrait du CV)
- Étudiant Master 2 — Développement full-stack (Java / Angular). :contentReference[oaicite:1]{index=1}  
- Passionné par les architectures microservices, la sécurité (Keycloak, JWT), la containerisation Docker et le cloud (Azure). :contentReference[oaicite:2]{index=2}

---

### 🔧 Compétences clés
**Backend:** Java · Spring Boot · Spring Cloud (Gateway, Eureka) · Spring Security · JWT · Keycloak  
**Bases de données:** MySQL · PostgreSQL · Redis (caching)  
**Frontend:** Angular · TypeScript · HTML5 · CSS3 · Tailwind CSS  
**DevOps / Cloud:** Docker · Azure (Blob Storage, Cache for Redis, ACR) · GitHub Actions  
**Tests:** JUnit · Mockito  
**Outils:** Git · Postman · Swagger · Maven

---

### 🧩 Projets sélectionnés
> Détails extraits du CV : API e-commerce, microservices, Redis, Keycloak, Azure. :contentReference[oaicite:3]{index=3}

#### Kida-Store (Application e-commerce — projet personnel)
- **Stack :** Spring Boot (REST API), Angular (front), Keycloak (auth RBAC), MySQL, Redis, Azure Blob Storage.  
- Fonctionnalités : authentification & rôles (ADMIN/USER), gestion produits, panier, commandes, upload d’images sur Blob, caching Redis.
- Conseils pour exposer le projet : ajouter un README dédié par service + scripts Docker Compose pour lancer localement.

#### API Spring Boot avec cache Redis
- API REST optimisée avec Spring Data Redis pour réduire le temps de réponse sur requêtes fréquentes.
- Conteneurisation via Docker.

#### Architecture e-commerce (Microservices)
- Architecture 5 services (Gateway, Eureka, Config Server + services métiers), containerisation et orchestration via Docker Compose.

---

### 📂 Repos recommandés à pinner
- `kida-store-backend` — API Spring Boot + Docker + Redis  
- `kida-store-frontend` — Angular 17 standalone + Keycloak integration  
- `microservices-ecommerce` — exemple architecture Gateway/Eureka/Config  
- `demo-redis-cache` — petite app démonstration Redis + Spring Data

*(Crée ces README détaillés dans chaque repo — guide d’installation, run via Docker Compose, et captures d’écran.)*

---

### 🔗 Contact / Réseaux
- Email : [abdelilahraees@gmail.com](mailto:abdelilahraees@gmail.com). :contentReference[oaicite:4]{index=4}  
- LinkedIn : https://www.linkedin.com/in/abdelilah-benkida-635372222. :contentReference[oaicite:5]{index=5}  
- GitHub : https://github.com/abdelilahraees. :contentReference[oaicite:6]{index=6}  
- Téléphone : +212 628 752 146. :contentReference[oaicite:7]{index=7}

---

### 📊 Stats & badges
<!-- Remplace `abdelilahraees` par ton username si tu changes -->
![Abdelilah's GitHub stats](https://github-readme-stats.vercel.app/api?username=abdelilahraees&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=abdelilahraees&layout=compact&theme=radical)

---

### 🛠️ Template « How to run » (à ajouter dans chaque repo)
```bash
# cloner
git clone https://github.com/abdelilahraees/kida-store-backend.git
cd kida-store-backend

# builder et lancer avec Docker Compose
docker compose up --build

# ou exécuter localement (prérequis : JDK, Maven, MySQL)
mvn clean install
java -jar target/app.jar

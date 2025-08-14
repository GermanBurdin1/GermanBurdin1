Salut, je m'appelle German ! Je cherche un CDI dans le Développement Web, mobile ou d'application dans les Côtes d'Armor.

# Projet sur lequel je travaille actuellement

## Plateforme d’apprentissage des langues — Architecture Microservices

Projet en cours : une plateforme **d’e-learning linguistique** bâtie sur une **architecture microservices**.  
Le **front-end** est développé en **Angular** et le **back-end** est découpé en plusieurs services NestJS spécialisés (authentification, gestion des leçons, vocabulaire, fichiers, notifications, statistiques, etc.), chacun étant **isolé**, **testable** et **déployable indépendamment**.  
Les déploiements sont facilités par l’utilisation de **migrations par service** et d’une CI/CD à granularité fine.

---

## Stack technique

- **Front-end** : Angular (CLI 18.x), SPA typée TypeScript  
- **Back-end** : NestJS (TypeScript) avec TypeORM et PostgreSQL  
- **Base de données** : PostgreSQL (migrations gérées par chaque microservice)  
- **Tests** : Unitaires et e2e (dossier `test/` dans chaque service)  
- **Architecture** : Microservices REST indépendants, communication via API HTTP  
- **Supervision** : Application Java/Spring Boot pour la gestion interne et le suivi de l’activité

---

## Services principaux

- **Front-end** : [teach_lang_app](https://github.com/GermanBurdin1/teach_lang_app) — Application Angular pour les apprenants et enseignants  
- **Authentification** : [dede-auth-service](https://github.com/GermanBurdin1/dede-auth-service) — Authentification, gestion des utilisateurs, confirmation d’email  
- **Gestion des leçons** : [lesson-service](https://github.com/GermanBurdin1/lesson-service) — CRUD et règles métier pour les leçons  
- **Vocabulaire** : [vocabulary-service](https://github.com/GermanBurdin1/vocabulary-service) — Gestion des mots, listes et progression  
- **Fichiers** : [file-service](https://github.com/GermanBurdin1/file-service) — Téléversement et gestion des ressources pédagogiques  
- **Notifications** : [notification-service](https://github.com/GermanBurdin1/notification-service) — Envoi et suivi des notifications (email, etc.)  
- **Statistiques** : [statistics_lang](https://github.com/GermanBurdin1/statistics_lang) — Collecte d’événements et indicateurs d’usage  
- **Divers (WIP)** : [mm_service](https://github.com/GermanBurdin1/mm_service) — Service technique en cours de développement

---

## Outil de supervision (Java / Spring Boot)

Projet connexe **EMS** pour permettre aux managers et autres acteurs de suivre l’activité liée à la plateforme :  
➡️ [esm](https://github.com/GermanBurdin1/esm) — Application **Java 21**, **Spring Boot 3.2.1**, **PostgreSQL**, avec documentation Swagger/OpenAPI et orchestration via Docker Compose.

---

## Aperçu architectural

```plaintext
[ Front-End Angular ]  --->  [ Auth Service ]       --->  [ PostgreSQL ]
                           |  [ Lesson Service ]    --->  [ PostgreSQL ]
                           |  [ Vocabulary Service ]--->  [ PostgreSQL ]
                           |  [ File Service ]      --->  [ PostgreSQL ]
                           |  [ Notification Service]
                           |  [ Statistics Service ]
                           |  [ mm_service (WIP) ]
                           |
                         [ Application EMS - Java/Spring Boot ]

👨‍💻 À mon propos :

Mon intérêt pour le web a été suscité lors de mon initiation au langage SQL en
octobre 2021, à travers une formation en ligne sur Data Analytics. 
Cette expérience a été un tournant décisif, m'incitant à privilégier la voie du
développement web plutôt que de poursuivre dans le data analytics.
Ma passion pour le développement web a débuté avec une formation en ligne sur
"apprendre à coder", une étape initiale où j'ai fait mes premiers pas dans le domaine du dév.
Après cette expérience enrichissante, j’ai eu l’opportunité de me consacrer
pleinement à une formation approfondie du 17 janvier au 26 octobre 2023. Cette
formation m’a permis d'acquérir des compétences essentielles en développement
web, notamment en HTML, CSS, JavaScript, ainsi que dans des concepts de
programmation avancés. <br>


![Dynamic Snake SVG](https://raw.githubusercontent.com/GermanBurdin1/snake/master/snake.svg) <br><br>

---
⚡ Etudiant en formation à Metz Numéric School Bachelor Développeur full stack en présentiel [MNS]([https://www.metz-numeric-school.fr/fr/formations/developpement-informatique/developpeur-web-et-web-mobile](https://www.metz-numeric-school.fr/formations/developpement-informatique/bachelor-developpeur-full-stack-et-alternance-1-an/). <br><br>
__________________________________________________
🌱 J'ai terminé les cours de développement web de [HTML Academy](https://github.com/htmlacademy) ! <br><br>

___________________
🤝 Réseaux sociaux : <br><br>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/german-burdin) 
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=flat&logo=telegram&logoColor=white)](https://t.me/Germanburdin)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/33675738495) 
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:germanburdin1@gmail.com) 
<br><br>

________________
💻 Technologies : <br> 
| Back-End      | Front-End      | Bases de données | Outils      |
|---------------|----------------|------------------|-------------|
| ![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat&logo=php&logoColor=white) | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white) | ![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white) |
| ![Java](https://img.shields.io/badge/-Java-007396?style=flat&logo=java&logoColor=white) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) | ![WordPress](https://img.shields.io/badge/-WordPress-21759B?style=flat&logo=wordpress&logoColor=white) |
| ![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=flat&logo=spring&logoColor=white) | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) |  | ![phpMyAdmin](https://img.shields.io/badge/phpMyAdmin-6C78AF?style=flat) |
| ![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat&logo=nestjs&logoColor=white) | ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) |  |  |
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) | ![Angular](https://img.shields.io/badge/-Angular-DD0031?style=flat&logo=angular&logoColor=white) |  |  |
|  | ![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black) |  |  |
|  | ![jQuery](https://img.shields.io/badge/-jQuery-0769AD?style=flat&logo=jquery&logoColor=white) |  |  |
|  | ![Bootstrap](https://img.shields.io/badge/-Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white) |  |  |



<br><br>
_________
🛠 Applications : <br><br>
![Canva](https://img.shields.io/badge/-Canva-00C4CC?style=flat&logo=canva&logoColor=white)
![Figma](https://img.shields.io/badge/-Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)
![Google Analytics](https://img.shields.io/badge/Google%20Analytics-E37400?style=flat&logo=googleanalytics&logoColor=white)
![Notion](https://img.shields.io/badge/-Notion-000000?style=flat&logo=notion&logoColor=white)



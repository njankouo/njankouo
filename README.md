# 👨‍💻 NJANKOUO NDAM DAIROU - Portfolio Full Stack & Systèmes d'Information

> Titulaire d'un Master en Systèmes d'Information et Génie Logiciel (SIGL), ce portfolio présente mes réalisations en tant que développeur Full Stack polyglotte, expert dans la conception et la mise en œuvre de solutions logicielles robustes et scalables.

[![Build Status](https://img.shields.io/badge/Status-Actif-brightgreen)](https://[portfolio-njankouo.vercel.app].com)
[![Version](https://img.shields.io/badge/Version-v1.0-blue)](https://github.com/[njankouo]/[])
[![Technologies](https://img.shields.io/badge/Frontend-%20React%20%7C%20Tailwind-61DAFB)](https://reactjs.org/)
[![Backend](https://img.shields.io/badge/Backend-Django%20%7C%20Node.js-000000)](https://www.djangoproject.com/)

## 🔗 Liens Rapides

* **Voir le Portfolio en Ligne :** https://portofolio-njankouo.vercel.app
* **LinkedIn :** [https://linkedin.com/in/[njankouo]](https://linkedin.com/in/njankouo)
* **Contacter :** dairounjankouo2019@gmail.com (mailto:dairounjankouo2019@gmail.com)

---

## 📖 Table des Matières

1.  [Introduction & Objectifs](#introduction--objectifs)
2.  [Stack Technique (La Boîte à Outils)](#stack-technique-la-boîte-à-outils)
3.  [Fonctionnalités du Portfolio](#fonctionnalités-du-portfolio)
4.  [Démarrage Rapide (Développement Local)](#démarrage-rapide-développement-local)
5.  [Architecture](#architecture)
6.  [Licence](#licence)

---

## 1. 💡 Introduction & Objectifs

Ce projet est une vitrine de mon expertise technique, démontrant ma capacité à gérer des projets de génie logiciel de bout en bout, de l'architecture du système à l'interface utilisateur.

En tant que diplômé SIGL, l'accent est mis non seulement sur le code, mais aussi sur :

* **L'architecture logicielle :** Conception d'APIs RESTful et GraphQL.
* **La performance :** Optimisation des requêtes (Postgres/MySQL) et du rendu (React/Tailwind CSS).
* **La polyvalence :** Capacité à naviguer entre les écosystèmes Python (Django), JavaScript (Node/React) et PHP (Laravel).

## 2. 🚀 Stack Technique (La Boîte à Outils)

Mon expertise repose sur une stack large, me permettant de choisir les outils les plus appropriés pour chaque cas d'usage.

| Catégorie | Outils Majeurs | Expertise |
| :--- | :--- | :--- |
| **Frontend Web** | **React**, **Tailwind CSS**, Bootstrap | Interfaces utilisateur modernes, réactives et performantes. |
| **Frontend Mobile** | **React Native** | Développement d'applications mobiles multiplateformes natives. |
| **Backend Python** | **Django** (avec Django Rest Framework) | Développement rapide d'APIs robustes et scalables. |
| **Backend JavaScript** | **Node.js** (Express/Koa), **API REST**, **GraphQL** | Microservices, architecture sans serveur et communication efficace des données. |
| **Backend PHP** | **Laravel**, **PHP** | Maîtrise des frameworks traditionnels pour la gestion de projets legacy ou monolithiques. |
| **Bases de Données** | **PostgreSQL**, **MySQL** | Conception de schémas de données, optimisation des requêtes complexes. |
| **Déploiement/Ops**| **Nginx** | Serveur web haute performance, reverse proxy, équilibrage de charge. |

## 3. ✨ Fonctionnalités du Portfolio

Le portfolio lui-même a été développé en utilisant une architecture moderne (par exemple, React pour le Front et une API Node.js ou Django pour les données).

* **Interface Réactive :** Utilisation de **Tailwind CSS** pour garantir un design fluide et cohérent sur tous les appareils.
* **Affichage Dynamique des Projets :** Les données des projets sont chargées via une **API REST** (ou **GraphQL**, selon la configuration) gérée par Node.js/Django.
* **Démonstrations Intégrées :** Chaque projet majeur affiche les technologies utilisées (badges) et un lien vers le dépôt GitHub.
* **Optimisation des Assets :** Utilisation d'outils modernes pour minimiser le temps de chargement.

## 4. ▶️ Démarrage Rapide (Développement Local)

Pour lancer une instance locale de ce portfolio, suivez les étapes suivantes.

### Prérequis

* Node.js (version 18+) & npm
* Python 3.x (si la partie backend utilise Django)
* Docker (recommandé pour la base de données PostgreSQL ou MySQL)

### Installation

```bash
# 1. Cloner le dépôt
git clone [https://github.com/](https://github.com/)[votre-utilisateur]/[votre-repo].git
cd [votre-repo]

# 2. Configurer l'environnement (Backend)
# Si vous utilisez un backend Node.js :
cd backend-api
npm install
cp .env.example .env # Configurer les variables DB/API

# 3. Lancer la base de données (Postgres exemple)
docker-compose up -d postgres

# 4. Lancer le backend
npm run start # Ou python manage.py runserver si c'est Django

# 5. Lancer le frontend (dans un nouveau terminal)
cd ../frontend-react
npm install
npm run dev

# Le portfolio est maintenant accessible sur http://localhost:3000

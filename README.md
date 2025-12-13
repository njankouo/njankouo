# 👨‍💻 NJANKOUO NDAM DAIROU - Portfolio Full Stack & Systèmes d'Information

> 🎓 Titulaire d'un Master en Systèmes d'Information et Génie Logiciel (SIGL), ce portfolio présente mes réalisations en tant que développeur Full Stack polyglotte, expert dans la conception et la mise en œuvre de solutions logicielles **robustes et scalables**.

---

## 🏅 Statut du Projet & Liens Rapides

| État et Dépôt | Liens Essentiels | Contact |
| :--- | :--- | :--- |
| [![Build Status](https://img.shields.io/badge/Status-Actif-brightgreen)](https://portfolio-njankouo.vercel.app) | **Voir le Portfolio :** [https://portfolio-njankouo.vercel.app](https://portfolio-njankouo.vercel.app) | **Email :** [dairounjankouo2019@gmail.com](mailto:dairounjankouo2019@gmail.com) |
| [![Version](https://img.shields.io/badge/Version-v1.0-blue)](https://github.com/njankouo/[votre-repo]) | **LinkedIn :** [https://linkedin.com/in/njankouo](https://linkedin.com/in/njankouo) | **GitHub :** https://github.com/njankouo/ |

---

## 📖 Sommaire Détaillé

1.  [Introduction & Objectifs](#1-💡-introduction--objectifs)
2.  [Stack Technique (La Boîte à Outils)](#2-🚀-stack-technique-la-boîte-à-outils)
3.  [Fonctionnalités du Portfolio](#3-✨-fonctionnalités-du-portfolio)
4.  [Portfolio Live : Projets Réalisés](#4-🌐-portfolio-live-projets-réalisés)
5.  [Démarrage Rapide (Développement Local)](#5-▶️-démarrage-rapide-développement-local)
6.  [Architecture](#6-🏗️-architecture)
7.  [Licence](#7-📄-licence)

---

## 1. 💡 Introduction & Objectifs

Ce projet est une vitrine de mon expertise technique, démontrant ma capacité à gérer des projets de génie logiciel de bout en bout, de l'architecture du système à l'interface utilisateur.

En tant que diplômé SIGL, l'accent est mis non seulement sur le code, mais aussi sur :

* **L'architecture logicielle :** Conception d'APIs RESTful et GraphQL.
* **La performance :** Optimisation des requêtes (**Postgres/MySQL**) et du rendu (**React/Tailwind CSS**).
* **La polyvalence :** Capacité à naviguer entre les écosystèmes **Python** (Django), **JavaScript** (Node/React) et **PHP** (Laravel).

---

## 2. 🚀 Stack Technique (La Boîte à Outils)

Mon expertise repose sur une stack large, me permettant de choisir les outils les plus appropriés pour chaque cas d'usage.

| Catégorie | Outils Majeurs | Expertise |
| :--- | :--- | :--- |
| **Frontend Web** | **React**, **Tailwind CSS**, Bootstrap | Interfaces utilisateur modernes, réactives et performantes. |
| **Frontend Mobile** | **React Native** | Développement d'applications mobiles multiplateformes natives. |
| **Backend Python** | **Django** (avec DRF) | Développement rapide d'APIs robustes et scalables. |
| **Backend JavaScript** | **Node.js**, **API REST**, **GraphQL** | Microservices, architecture sans serveur et communication efficace. |
| **Backend PHP** | **Laravel**, **PHP** | Maîtrise des frameworks traditionnels. |
| **Bases de Données** | **PostgreSQL**, **MySQL** | Conception de schémas de données, optimisation des requêtes complexes. |
| **Déploiement/Ops**| **Nginx** | Serveur web haute performance, reverse proxy, équilibrage de charge. |

---

## 3. ✨ Fonctionnalités du Portfolio

Le portfolio lui-même a été développé en utilisant une architecture moderne.

* **Design Révolutionnaire :** Utilisation de **Tailwind CSS** pour garantir un design fluide, réactif et modulaire.
* **Contenu Dynamique :** Affichage des projets géré via une **API REST** (ou **GraphQL**) servie par Node.js/Django.
* **Lisibilité :** Design optimisé pour minimiser le temps de chargement et maximiser l'expérience utilisateur.

---

## 4. 🌐 Portfolio Live : Projets Réalisés

Ces réalisations démontrent ma capacité à délivrer des produits fonctionnels dans des environnements variés :

| Projet | Description | Technologies Clés | Lien en Ligne |
| :--- | :--- | :--- | :--- |
| **Operaplus** | Plateforme intégrée de services/gestion. | [React, Django, PostgreSQL] | [https://operaplus.org](https://operaplus.org) |
| **Edutack** | Solution e-learning ou de gestion académique. | [React, Laravel, MySQL, Nginx] | [https://edutack.operaplus.org](https://edutack.operaplus.org) |
| **MboaMarket** | Application de Place de marché (e-commerce). | [Node.js, React Native, API REST] | [https://mboamarket.com](https://mboamarket.com) |
| **Africasurg** | Application ou site dédié au secteur médical/chirurgical. | [Python/Django, React, Tailwind CSS] | [https://africasurg.com](https://africasurg.com) |

---

## 5. ▶️ Démarrage Rapide (Développement Local)

Pour lancer une instance locale, assurez-vous d'avoir les [Prérequis](#prérequis) puis suivez les étapes d'installation ci-dessous.

### Prérequis

* **Node.js** (v18+) & **npm**
* **Python 3.x**
* **Docker** (fortement recommandé pour la base de données)

### Installation

```bash
# 1. Cloner le dépôt
git clone [https://github.com/njankouo/](https://github.com/njankouo/)[votre-repo].git
cd [votre-repo]

# 2. Lancer la base de données (Postgres exemple)
docker-compose up -d postgres

# 3. Configurer et démarrer le backend (Node.js/Django)
cd backend-api
npm install         # Installe les dépendances Node
cp .env.example .env # Configurer les variables DB/API
npm run start       # Ou python manage.py runserver si c'est Django

# 4. Lancer le frontend (dans un nouveau terminal)
cd ../frontend-react
npm install
npm run dev

# 🌍 Le portfolio est maintenant accessible sur http://portfolio-njankouo.vercel.app

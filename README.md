# AdonisJS
Découverte du framework AdonisJS.

# Plan de formation AdonisJS – Création d’un Blog

## Description

Bienvenue dans ce projet de blog personnel développé avec AdonisJS, en mode step by step. L'objectif est de découvrir AdonisJS en profondeur tout en créant un projet concret.

---

## Prérequis

* Node.js v16 ou supérieur
* npm ou yarn
* Une base de données (SQLite, PostgreSQL, MySQL…)
* Git (optionnel)

---

## 🗺️ Roadmap d'apprentissage AdonisJS

**⚙️ 1. Initialisation du projet**

* Installation du CLI AdonisJS
* Création d’un nouveau projet
* Démarrage du serveur de développement

**🔀 2. Routes & Controllers**

* Comprendre le système de routes en AdonisJS v6
* Créer un controller simple
* Gérer les routes dynamiques (`/posts/:id`)
* Nommer les routes

**🧠 3. Comprendre le IoC (Inversion of Control)**

* Découvrir le système d’import basé sur les alias (`#controllers/...`)
* Comprendre comment fonctionne le conteneur IoC dans AdonisJS
* Avantages vs anciens systèmes de routing

**🗃️ 4. Base de données et ORM**

* Choix et configuration du moteur de base de données (SQLite, PostgreSQL, etc.)
* Création de la migration `posts`
* Création du model `Post`
* Utiliser Lucid ORM pour faire des requêtes simples
* Seed de données pour tester

**✍️ 5. CRUD complet pour les articles**

* Afficher tous les articles (`index`)
* Voir un article (`show`)
* Créer un article (`create` & `store`)
* Modifier un article (`edit` & `update`)
* Supprimer un article (`destroy`)

**🎨 6. Vues et Frontend**

* Utiliser Edge.js pour créer des templates
* Lier les données du backend aux vues
* Ajouter une base HTML/CSS simple

**🔐 7. Authentification**

* Installer le système d’authentification
* Enregistrer un utilisateur
* Connexion / Déconnexion
* Protéger certaines routes avec un middleware `auth`

**🧰 8. Validation et sécurité**

* Valider les formulaires avec les validators
* Protéger contre les injections SQL, CSRF, XSS, etc.
* Gestion des erreurs et messages personnalisés

**🛠️ 9. Services & organisation du code**

* Création de services personnalisés
* Réutilisation de logique métier
* Structuration claire du code avec des providers si besoin

**🧪 10. Tests**

* Tester les routes
* Tester les modèles
* Tester les règles de validation

**🚀 11. Déploiement**

* Préparer le build pour la production
* Déployer sur un VPS ou une plateforme comme Railway / Render / Heroku
* Configuration des variables d’environnement

**🧩 Bonus**

* Utiliser Websockets (commentaires en temps réel par exemple)
* API REST ou JSON API pour un frontend en React/Vue
* Upload de fichiers (ex : images d’articles)
* Pagination, filtres, recherche

---

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

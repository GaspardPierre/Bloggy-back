# 🎓 Bloggy Back-End 🚀

## 📚 Introduction

Bloggy est une plateforme conçue pour aider les jeunes en décrochage scolaire. Notre objectif est de redonner confiance à ces jeunes, de les valoriser et de les encourager à s'exprimer. Nous croyons fermement que chaque jeune a un potentiel unique et que Bloggy peut les aider à le découvrir et à le développer.

## 💻 Installation

Pour installer et configurer le serveur back-end et la base de données, suivez les étapes ci-dessous :

### 📋 Prérequis

- Node.js
- npm
- PostgreSQL

### 🛠️ Étapes d'installation

1. **Clonez le dépôt**

   Ouvrez votre terminal et exécutez la commande suivante pour cloner le dépôt :

git clone https://github.com/GaspardPierre/Bloggy-back.git


2. **Installez les dépendances**

Naviguez vers le répertoire du projet et installez les dépendances nécessaires avec npm :
cd Bloggy-back
npm install

3. **Configurez la base de données**

Définissez les variables d'environnement nécessaires pour la connexion à la base de données PostgreSQL et exécutez le script de création des tables :
export PGUSER=admin_bloggy
export PGPASSWORD=bloggy
export PGDATABASE=bloggy
psql -f scripts/1.create_tables.sql

Assurez-vous que vous avez `psql` installé et une instance de PostgreSQL en cours d'exécution.

4. **Lancez le serveur**

Une fois que tout est configuré, vous pouvez lancer le serveur avec la commande suivante :

npm start


Le serveur devrait maintenant être en cours d'exécution à l'adresse `http://localhost:3000`.

## 🤝 Contribution

Nous accueillons les contributions de tous ceux qui souhaitent aider à améliorer Bloggy. N'hésitez pas à soumettre des pull requests ou à ouvrir des issues si vous rencontrez des problèmes.

## 📜 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.













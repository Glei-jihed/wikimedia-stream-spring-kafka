# Projet Wikimedia Stream Spring Kafka

Ce projet, appelé "Wikimedia Stream Spring Kafka", a pour objectif de consommer une API Wikimedia, d'envoyer les données au cluster Apache Kafka, puis de les consommer avec un autre projet.

## Description du projet

Le dossier du projet contient deux sous-dossiers, chacun présentant un projet Spring Boot distinct :
- Un projet pour le producteur
- Un projet pour le consommateur

Le producteur est responsable de consommer l'API Wikimedia et d'envoyer les données au cluster Apache Kafka. Le consommateur, quant à lui, est chargé de récupérer les données du cluster Kafka pour un traitement ultérieur.

## Prérequis

Avant de pouvoir utiliser ce projet, veuillez vous assurer de respecter les étapes suivantes :

1. Installer et configurer Apache Kafka.
2. Lancer ZooKeeper et Apache Kafka.
3. Cloner ce dépôt et accéder au dossier du projet.
4. Lancer les deux projets Spring Boot (producteur et consommateur).

## Utilisation

Une fois les projets lancés et le cluster Kafka configuré, vous pouvez consommer les données en utilisant l'URL suivante avec Postman :

[http://localhost:8081/api/v1/wikimedia](http://localhost:8081/api/v1/wikimedia)

Assurez-vous que les projets Spring Boot sont en cours d'exécution et que le cluster Kafka est opérationnel pour une utilisation correcte de l'API.

## Contact

Bonjour ! Je suis GLEI Jihed, le développeur de ce projet. Passionné par la création d'applications innovantes, je suis disponible pour répondre à vos questions et discuter de toute suggestion d'amélioration.

Vous pouvez me contacter par e-mail à jihed.glei@yahoo.com ou par téléphone au 0753129330. N'hésitez pas à me joindre, je serais ravi d'échanger avec vous !

---

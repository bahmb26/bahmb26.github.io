# Projet Cloud .NET et Azure — Architecture distribuée

## Description

Ce projet académique a été réalisé dans le cadre d’un devoir universitaire en informatique.

L’objectif était de transformer une base de code existante en une architecture Cloud moderne, distribuée et déployable automatiquement avec Microsoft Azure.

Le projet comprend une application MVC, une API REST, plusieurs Worker Services, une architecture orientée événements, une base de données NoSQL avec Azure Cosmos DB, un pipeline CI/CD et une conteneurisation complète avec Docker.

## Objectifs du projet

- Concevoir une architecture Cloud modulaire et distribuée.
- Séparer l’interface utilisateur, la logique d’affaires et les traitements en arrière-plan.
- Intégrer une API REST documentée avec Swagger.
- Utiliser Azure Event Hub pour transmettre les événements entre les services.
- Synchroniser les données avec Azure Cosmos DB.
- Automatiser le déploiement avec un pipeline YAML.
- Conteneuriser les composants avec Docker et docker-compose.
- Rédiger une documentation technique claire.

## Technologies utilisées

- C#
- .NET
- ASP.NET MVC
- API REST
- Swagger
- Docker
- docker-compose
- Azure DevOps
- Pipeline YAML
- Azure Blob Storage
- Azure Key Vault
- Azure App Configuration
- Azure Service Bus
- Azure Event Hub
- Azure Cosmos DB
- Azure Application Insights
- Git / GitHub

## Architecture du projet

Le projet est composé des éléments suivants :

- Application MVC : interface utilisateur.
- API REST : logique d’affaires principale.
- Worker_Content : traitement de contenu.
- Worker_Image : traitement d’images.
- Worker_CosmosSync : écoute les événements provenant d’Azure Event Hub et applique les modifications dans Cosmos DB.
- Projet Infrastructure : déploiement automatique des ressources Azure.
- Pipeline YAML : automatisation du déploiement.
- Docker Compose : exécution locale des services.

## Fonctionnalités principales

- Communication entre l’application MVC et l’API.
- Documentation des endpoints avec Swagger.
- Architecture orientée événements.
- Envoi et traitement d’événements avec Azure Event Hub.
- Stockage et synchronisation des données avec Azure Cosmos DB.
- Gestion des secrets avec Azure Key Vault.
- Configuration centralisée avec Azure App Configuration.
- Conteneurisation des composants avec Docker.
- Préparation d’un pipeline CI/CD avec YAML.

## Ce que j’ai appris

Ce projet m’a permis de renforcer mes compétences en développement .NET, architecture logicielle, Cloud Azure, DevOps et conteneurisation.

J’ai aussi appris à structurer une solution en plusieurs composants, à documenter une API, à utiliser une architecture orientée événements et à préparer un déploiement automatisé.

## Statut

Projet académique réalisé dans le cadre d’un devoir universitaire.

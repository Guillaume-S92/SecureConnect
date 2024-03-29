
﻿# SecureConnect

Projet de Gestion des Utilisateurs avec Spring Boot

## Description

Ce projet est une application de gestion des utilisateurs développée en utilisant Spring Boot, MySQL, Spring Security, Spring Data JPA, Thymeleaf, Spring Boot DevTools et Spring Web. Il fournit des fonctionnalités pour la création, la connexion et la gestion sécurisée des utilisateurs, ainsi qu'un tableau de bord distinct pour les utilisateurs et les administrateurs.

## Fonctionnalités

- **Création d'Utilisateurs:** Les utilisateurs peuvent s'inscrire en fournissant leur nom, adresse e-mail et mot de passe.
- **Connexion Sécurisée:** Les utilisateurs peuvent se connecter en toute sécurité à l'application à l'aide de leurs informations d'identification.
- **Sécurité:** L'application utilise Spring Security pour protéger les pages et les ressources, ainsi que le hachage bcrypt pour stocker les mots de passe de manière sécurisée dans la base de données.
- **FrontEnd:** L'interface est développée avec Thymeleaf 

## Technologies Utilisées

- Spring Boot
- MySQL Database
- Spring Security
- Spring Data JPA
- Thymeleaf
- Spring Boot DevTools
- Spring Web

## Prérequis

Avant de lancer l'application, assurez-vous d'avoir installé les prérequis suivants :
- JDK 8 ou version ultérieure
- Maven
- MySQL Database

## Installation et Utilisation

1. Cloner le repository depuis GitHub.
2. Configurer la base de données MySQL en modifiant les paramètres dans le fichier `application.properties`.
3. Compiler et exécuter l'application à l'aide de Maven : mvn spring-boot:run
4. Accéder à l'application à l'adresse suivante : [http://localhost:8080](http://localhost:8080)


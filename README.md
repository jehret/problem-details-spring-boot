# Spring Boot 3 - Gestion des Erreurs HTTP avec Problem Details (RFC 7807)

**Dates** : du 19/01/25 au 02/02/25

**Difficulté** :  Moyenne

**Technologies** : Spring Boot 3 - Java 17+ ou Kotlin

## Description

Avec **Spring Boot 3**, la gestion des erreurs HTTP a évolué pour adopter le format **Problem Details** défini par la spécification **RFC 7807**. Ce format standardisé permet de fournir des réponses d'erreur structurées et plus détaillées. Ce challenge vous invite à explorer cette nouvelle manière de gérer les erreurs et à comparer avec l'approche précédente utilisée dans **Spring Boot 2**.

## Objectif

1. Implémenter une gestion des erreurs dans une API REST en utilisant le format Problem Details.
2. Générer une erreur et la tester avec un client type Postman.
3. Comparer avec l'approche traditionnelle de gestion des erreurs dans Spring Boot 2.
4. Documenter les avantages de la nouvelle méthode par rapport à l'ancienne.

## Exigences

1. Création d'une API REST :
  - Implémenter quelques endpoints REST (par exemple, CRUD pour une entité `Product`).
  - Simuler différentes erreurs HTTP (404, 400, 500, etc.).
2. Gestion des Erreurs avec Problem Details :
  - Configurer le projet pour utiliser Problem Details (disponible nativement dans Spring Boot 3).
  - Retourner des réponses au format RFC 7807 pour les erreurs HTTP.
3. Documentation et Comparaison avec Spring Boot 2 :
  - Décrire comment les erreurs étaient gérées en Spring Boot 2 (par exemple, en utilisant `@ControllerAdvice` et/ou `@ExceptionHandler`).
  - Fournir un exemple de gestion d'erreur dans Spring Boot 2 et comparer avec la nouvelle approche.
  - Mettre en évidence les avantages de l'utilisation de Problem Details (standardisation, meilleure lisibilité des erreurs, etc.).

## Bonus

1. Client :
  - Créer un petit code JS capable d'intercepter les Problem Details et les afficher dans une bannière d'erreur.
2. Innovation : Il n'existe pas encore un outil très spécialisé dans la gestion et la visualisation des **Problem Details**. Cela représente une opportunité de créer un service ou un outil dédié< Imaginez ce que cet outil pourrait être et si vous voulez démarrer quelque chose, c'est peut-être là l'opportunité de votre vie 😉. Quelques idées..., l'outil pourrait être un outil web, une extension Swagger-Open API, ou une extension Postman...et pourrait par exemple :
  - Automatiquement regrouper et classer les erreurs basées sur le type et status.
  - Offrir des insights sur les erreurs les plus fréquentes et les corrélations entre différents types d'erreurs.
  - Intégrer avec des systèmes de tickets pour faciliter la résolution d'incidents.

## Evaluation
  
  - Bonne utilisation de Problem Details en Spring Boot 3.
  - Qualité de la documentation et de la comparaison entre les approches de Spring Boot 2 et 3.
  - Clarté de la documentation et des exemples fournis.
  - Design et implemenntation des Bonus

## Récompenses
- Vainqueur : 10 pts
- 2ème : 5 pts
- 3ème : 2 pts

Rappel: Les participants accumulent des points en fonction de leur performance dans les challenges. Ces points peuvent être convertis en cartes cadeaux Prezzy, utilisables pour des achats en ligne ou en magasin dans n'importe quelle devise.

💬 **N'oubliez pas** de poser vos questions sur le serveur Discord pour toute clarification ou aide sur ce challenge. Bonne chance à tous et amusez-vous bien ! 🎉


# TP4 : Intégration de Ribbon pour l'Équilibrage de Charge

## Description

Ce TP met en œuvre **Ribbon**, un client d'équilibrage de charge côté serveur, pour répartir les requêtes entre plusieurs instances de microservices dans un environnement Spring Boot.

## Fonctionnalités :

- Équilibrage de charge entre plusieurs instances (`Ribbon` avec `@LoadBalanced`).
- Intégration avec **RestTemplate**.
- Configuration des instances via `application.yml`.
- Tests des microservices avec des outils comme Postman ou cURL.

## Technologies :

- Java 17
- Spring Boot
- Spring Cloud Netflix Ribbon

## Commandes pour exécuter :

1. Lancer plusieurs instances des microservices (exemple : `8081`, `8082`).
2. Tester les APIs via les endpoints :
   - `http://localhost:8081/products`
   - `http://localhost:8082/users`

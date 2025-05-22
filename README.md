# Simulation de Scraping d'API (Type Facebook) avec Mécanisme de Protection
## Présentation
Ce projet simule un scraping de données personnelles via une interface web, similaire aux attaques subies par des plateformes comme Facebook. L’objectif est de démontrer la facilité avec laquelle une API non protégée peut être exploitée, tout en illustrant l'impact de contre-mesures simples comme la limitation de requêtes (rate limiting).

## Objectifs pédagogiques
Simuler une attaque de scraping massif sur une API publique.

Illustrer l'effet de mécanismes de protection (limitation de requêtes par seconde).

Comprendre les risques liés à une mauvaise configuration des APIs.

Sensibiliser à l’importance de la vigilance et de la sécurité API.

## Technologies utilisées
HTML5 / CSS3

JavaScript Vanilla

Tailwind CSS (CDN)

## Fonctionnalités
Scraping simulé
Génération automatique de profils utilisateurs aléatoires (nom, email, téléphone...).

Insertion dynamique des données dans un tableau HTML.

Journalisation des actions (log des événements avec timestamp).

## Protection (Rate Limiting)
Possibilité d’activer/désactiver la protection contre le scraping.

Lorsqu’activée : bloque plus de 5 requêtes par seconde.

Comptage des requêtes effectuées et bloquées.

Réinitialisation automatique des compteurs à chaque (dé)activation.

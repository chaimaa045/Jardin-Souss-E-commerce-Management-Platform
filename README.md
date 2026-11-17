# 🌿 Souss Garden — Plateforme Digitale pour Paysagiste & Pépinière

<p align="center">
  <strong>Solution web Full-Stack tout-en-un combinant un site vitrine immersif, une boutique e-commerce et un back-office métier PWA.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js_16-React_19-black?style=for-the-badge&logo=next.js" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-Tailwind_CSS_v4-3178C6?style=for-the-badge&logo=typescript" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Spring_Boot_3.2-Java_17-6DB33F?style=for-the-badge&logo=spring-boot" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-Cloud_DB-336791?style=for-the-badge&logo=postgresql" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Spring_Security-JWT-green?style=for-the-badge&logo=spring-security" alt="Security" />
  <img src="https://img.shields.io/badge/PWA-Installable-blueviolet?style=for-the-badge&logo=pwa" alt="PWA" />
</p>

---

##  Présentation du Projet

**Souss Garden** est une plateforme conçue pour moderniser et digitaliser l'activité d'une entreprise d'aménagement paysager et d'horticulture. 

Le projet répond à trois besoins concrets :
1. **Mettre en valeur le savoir-faire artisanal** à travers un portfolio élégant de chantiers paysagers.
2. **Vendre directement en ligne** des plantes, du mobilier d'extérieur et du matériel de jardinage.
3. **Fournir un outil de gestion clé en main (Back-Office)** accessible sur smartphone et ordinateur pour gérer les stocks, suivre les commandes et imprimer les reçus de livraison.

---

##  Les 3 Piliers de l'Application

### 1. La Vitrine & Portfolio Paysager
- **Showcase des chantiers** : Présentation des réalisations (création d'espaces verts, pose de gazon, terrasses, arrosage automatique) avec galeries photos haute résolution et affichage en Lightbox.
- **Conversion client** : Formulaire de demande de devis en ligne et redirection directe vers WhatsApp pour un contact immédiat.
- **Bilingue & Accessible** : Interface entièrement traduite en **Français** et en **Arabe** avec prise en charge native du sens de lecture **RTL** (droite à gauche).

### 2. La Boutique E-Commerce
- **Catalogue dynamique** : Navigation fluide avec filtres par catégories (plantes, arbres fruitiers, outillage, engrais) et recherche instantanée.
- **Gestion des stocks en temps réel** : Affichage automatique de l'état du stock avec blocage de l'achat en cas de rupture.
- **Tunnel d'achat optimisé** : Panier interactif persistant et commande simplifiée en **Paiement à la livraison** (*Cash on Delivery*).

### 3. Le Back-Office Administrateur (PWA)
- **Application installable (PWA)** : Utilisable comme une application native sur Android, iOS et Windows sans passer par les stores.
- **Tableau de bord** : Vue synthétique des métriques clés (commandes en cours, chiffre d'affaires estimé, alertes stock).
- **Gestion du catalogue & médias** : Ajout et mise à jour des produits et chantiers avec hébergement et optimisation automatique des images via CDN.
- **Traitement des commandes & Facturation** : Suivi des statuts de livraison et génération de reçus professionnels imprimables intégrant les identifiants légaux de l'entreprise (ICE, RC, Patente).

---

##  Stack Technique & Architecture

L'application repose sur une architecture découplée, moderne et performante :

###  Frontend
- **Next.js 16 (App Router) & React 19** : Rendu hybride pour un chargement instantané et un référencement naturel (SEO) optimal.
- **TypeScript** : Typage statique de bout en bout garantissant la fiabilité du code.
- **Tailwind CSS v4 & Framer Motion** : Design moderne, animations fluides et interface totalement adaptative (Desktop, Tablette, Mobile).
- **next-intl** : Moteur d'internationalisation performant pour la gestion des deux langues (FR / AR).
- **React Hook Form & Zod** : Validation rigoureuse des formulaires côté client.

###  Backend (API REST)
- **Spring Boot 3.2 (Java 17)** : Architecture en couches (Contrôleurs, Services, Repositories, DTOs).
- **Spring Security 6 & JWT** : Authentification sans état (*stateless*) via des tokens sécurisés pour protéger les routes d'administration.
- **Spring Data JPA & Hibernate** : Gestion optimisée de la persistance des données.
- **Cloudinary SDK** : Gestion et distribution optimisée des images et médias.
- **Spring Mail** : Notifications par e-mail lors des nouvelles commandes et demandes de contact.

###  Données & Hébergement
- **PostgreSQL** : Base de données relationnelle garantissant l'intégrité transactionnelle des commandes et des stocks.
- **Architecture Conteneurisée** : Préparée pour le déploiement multi-environnements avec Docker.

---

## Points Forts & Spécificités Techniques

- **Accès discret au Back-office** : Point d'entrée discret et sécurisé vers l'administration pour préserver l'esthétique du site vitrine.
- **Impression prête à l'emploi** : Mise en page CSS spécifique (`@media print`) pour imprimer des bons de commande propres au format papier ou ticket pour les livreurs.
- **Expérience mobile first** : Conçu avant tout pour être manipulé aisément sur le terrain par les artisans et livreurs via smartphone.
- **Sécurité renforcée** : Hashage des mots de passe en **BCrypt**, validation des DTOs avec Jakarta Validation et politiques CORS strictes.

---

<p align="center">
  Développé pour <strong>Jardin Souss</strong> • 2026
</p>

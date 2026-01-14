# Subscription Orchestration Patterns

🇬🇧 English | 🇫🇷 Français

---

## 🇬🇧 Overview

This repository documents common patterns and pitfalls when managing subscriptions in complex B2B and hybrid SaaS products.

As SaaS platforms grow, subscription logic often becomes fragmented across:
- billing platforms (Stripe, Chargebee, etc.)
- identity providers (SSO / IAM)
- custom access rules
- CRM and internal business logic

This fragmentation leads to duplicated logic, inconsistent access rights, and high maintenance costs.

---

## 🇬🇧 What this repository covers

- Subscription vs billing responsibilities  
- B2B subscription models (organizations, seats, roles)  
- Entitlements and access control patterns  
- Common architectural mistakes  
- Orchestration approaches for scalable SaaS platforms  

---

## 🇫🇷 Présentation

Ce dépôt documente les principaux patterns et écueils rencontrés lors de la gestion des abonnements dans des produits SaaS B2B ou hybrides.

Avec la croissance d’un produit, la logique d’abonnement se retrouve souvent dispersée entre :
- les outils de facturation (Stripe, Chargebee, etc.)
- les fournisseurs d’identité (SSO / IAM)
- des règles d’accès spécifiques
- le CRM et la logique métier interne

Cette dispersion entraîne une duplication de la logique métier, des incohérences d’accès et une maintenance complexe.

---

## 🇫🇷 Ce que couvre ce dépôt

- Différence entre abonnement et facturation  
- Modèles d’abonnement B2B (organisations, sièges, rôles)  
- Gestion des droits et des entitlements  
- Erreurs d’architecture fréquentes  
- Approches d’orchestration pour des plateformes SaaS scalables  

---

## 🔗 Related platform / Plateforme associée

These patterns are centralized and implemented in **Fleetwall**, a subscription and identity orchestration platform designed for complex B2B SaaS architectures.

👉 https://www.fleetwall.app

---

## 📌 Status

This repository is documentation-focused and will evolve over time.

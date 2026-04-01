# 🚌 GOLink - Le Bus Modulaire de Demain

**GOLink** est une plateforme web moderne présentant un concept de mobilité urbaine révolutionnaire : des bus autonomes, 100 % électriques et modulables qui s'assemblent en temps réel selon l'affluence.

![Version Desktop](public/images/social-preview.jpg)

## 🚀 Concept
L'objectif de GOLink est de mettre fin aux trajets à vide et de fluidifier le trafic urbain. Grâce à une application intelligente, le réseau anticipe les besoins des usagers et dispatch des modules de 4 à 12 places qui peuvent se coupler dynamiquement.

## 🛠️ Stack Technique

Ce projet a été développé avec une attention particulière portée à la performance et à l'expérience utilisateur (UX/UI).

* **Framework :** [Astro 4.x](https://astro.build/) (Utilisation de l'architecture en îles et du ClientRouter).
* **Composants :** Architecture basée sur des composants Astro réutilisables.
* **Stylisation :** CSS natif (Modern CSS) avec un système de grille de type "Bento Grid".
* **Animations :** Intersection Observer API pour les déclenchements au scroll et transitions fluides.
* **Typographie :** Funnel Sans & Funnel Display.

## 📦 Structure du Projet

Le projet suit la structure standard d'Astro :

```text
/
├── public/              # Assets statiques (Images, Favicons)
├── src/
│   ├── components/      # Composants UI (Buttons, BentoGrid, Cards)
│   │   ├── global/      # Header, Footer
│   │   └── ui/          # Éléments d'interface réutilisables
│   ├── layouts/         # Layout principal (SEO, Metadata, Google Fonts)
│   └── pages/           # Pages du site (Accueil, Fonctionnement, Avantages)
└── astro.config.mjs     # Configuration du framework
# 🥖 Upper-Crust

*(English version below)*

> **Application iPad native pour optimiser la gestion des commandes et la production en boulangerie.**

[![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)](https://developer.apple.com/swift/)
[![Platform](https://img.shields.io/badge/Platform-iPadOS-lightgrey.svg)](https://www.apple.com/ipados/)

---

## 🇫🇷 Version Française

### Contexte
Dans une boulangerie artisanale, la communication entre la boutique (vente) et le laboratoire (production) est critique. Ce projet vise à remplacer le cahier de commandes papier par une solution numérique efficace sur iPad.

L'objectif est double : permettre aux vendeurs de prendre des commandes anticipées rapidement et offrir aux pâtissiers une vue claire de la production à réaliser.

### Fonctionnalités

#### Côté Boutique (Front Office)
* **Prise de commande intuitive :** Interface tactile optimisée pour saisir rapidement les produits (pains, viennoiseries, gâteaux) et la date de retrait.
* **Vue Calendrier :** Visualisation des commandes à venir pour les 7 prochains jours.
* **Gestion Client :** Historique des commandes et préférences (allergies, habitudes).

#### Côté Fournil / Labo (Back Office)
* **Calcul de Production (MRP) :** Agrégation automatique des commandes (ex: L'app indique "Besoin total : 40 croissants", au lieu de lister 10 commandes de 4).
* **Checklist Interactive :** Interface à gros boutons adaptée à une utilisation en cuisine (mains farinées) pour cocher les tâches réalisées.
* **Anti-Gaspillage :** Ajustement des quantités à produire basé sur la demande réelle.

### Stack Technique
* **Langage :** Swift 5
* **Interface :** SwiftUI (ou UIKit)
* **Stockage Local :** CoreData / SwiftData (Persistance des commandes hors-ligne)
* **Cible :** iPadOS (Optimisé pour iPad Pro / iPad Air)

### Installation et Démarrage

1.  **Cloner le projet :**
    ```bash
    git clone [https://github.com/votre-username/nom-du-projet.git](https://github.com/votre-username/nom-du-projet.git)
    ```
2.  **Ouvrir dans Xcode :**
    Ouvrez le fichier `.xcodeproj` (ou `.xcworkspace`).
3.  **Lancer :**
    Sélectionnez un simulateur iPad (ex: *iPad Pro 12.9"*) et faites `Cmd + R`.

---

## 🇬🇧 English Version

### 📄 Overview
In an artisanal bakery, communication between the shop (sales) and the lab (production) is critical. This project aims to replace the traditional paper order book with an efficient native iPad solution.

The goal is twofold: enable sales staff to take advance orders quickly and provide bakers with a clear, aggregated view of the required production.

###  Key Features

####  Front of House (Shop Mode)
* **Fast Order Entry:** Touch-optimized interface to quickly log products (breads, pastries, cakes) and pickup dates.
* **Calendar View:** Global view of upcoming orders for the next 7 days.
* **Customer Management:** Order history and preferences.

#### Back of House (Baker Mode)
* **Production Aggregation:** Automatically calculates total quantities needed (e.g., shows "Total need: 40 croissants" instead of 10 separate orders).
* **Interactive Checklist:** Large-button interface designed for kitchen use (flour-covered hands friendly) to mark items as "Baked".
* **Waste Reduction:** Production planning based on actual pre-orders.

### Tech Stack
* **Language:** Swift 5
* **UI Framework:** SwiftUI (or UIKit)
* **Local Storage:** CoreData / SwiftData (Offline persistence)
* **Target:** iPadOS (Optimized for iPad Pro / iPad Air)

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/project-name.git](https://github.com/your-username/project-name.git)
    ```
2.  **Open in Xcode:**
    Open the `.xcodeproj` (or `.xcworkspace`) file.
3.  **Run:**
    Select an iPad simulator (e.g., *iPad Pro 12.9"*) and press `Cmd + R`.

---

## Auteur / Author
**[Noémie Gil]**
* [LinkedIn](https://www.linkedin.com/in/no%C3%A9mie-gil-a5a856327/)
* [Portfolio](a venir)

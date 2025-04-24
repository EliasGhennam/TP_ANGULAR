# 📚 BiblioTech - Gestion de bibliothèque personnelle

> **TP Angular - Correction des bugs et complétion des fonctionnalités**

---

## 🚀 Présentation du projet

BiblioTech est une application web développée avec **Angular Standalone Components**.  
Elle permet aux utilisateurs de :
- 📖 Consulter leur collection de livres
- ➕ Ajouter de nouveaux livres
- ⭐ Gérer leurs livres favoris
- 🗑️ Supprimer des livres

Ce projet a été réalisé dans le cadre d'un **TP Angular** dont l'objectif était de corriger les bugs laissés par l'équipe précédente et de finaliser les fonctionnalités incomplètes.

---

## 🎯 Objectifs pédagogiques

- Comprendre et manipuler les concepts fondamentaux d’Angular :
  - ✅ Standalone Components
  - ✅ Directives personnalisées
  - ✅ Pipes existants et personnalisés
  - ✅ Services et gestion des données via HTTP
  - ✅ Routing et navigation (SPA)
  - ✅ Formulaires réactifs et validation
  - ✅ Communication entre composants
- Appliquer les bonnes pratiques de modularisation et de réutilisabilité du code.

---

## 🛠️ Fonctionnalités de l’application

- 🗂️ Navigation fluide sans rechargement de la page
- 📂 Structure modulaire avec composants réutilisables (header, footer)
- 📖 Affichage correct des catégories et descriptions avec pipes personnalisés :
  - Pipe `capitalizeFirst` pour transformer le titre
  - Pipe `truncate` pour limiter la longueur des descriptions avec des points de suspension
- ⭐ Mise en avant des favoris grâce à la directive `highlight` (gras + couleur conditionnelle)
- ✅ Gestion des actions utilisateurs avec alertes de confirmation ou d’erreur (ajout, suppression, modification de favori)
- 📝 Formulaire d’ajout de livre avec validations (required, minLength)
- ↩️ Bouton de retour fonctionnel vers la page précédente
- ❌ Aucun message d’erreur dans la console

---

## 📦 Installation et lancement

### 1. Clone du projet :
```bash
git clone [https://github.com/EliasGhennam/TP_ANGULAR]
cd epsi-tp-01
npm install
```
Lancement du site :
```bash
ng serve

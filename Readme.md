# Mini CRM Front-End Challenge

## Objectif

Développer l’interface front-end d’un mini CRM en **Next.js** pour une équipe commerciale.  
Le projet permet de :
- Consulter une liste de clients
- Visualiser la fiche détaillée d’un client
- Ajouter un nouveau client via un formulaire

---

## Stack technique

- **Next.js** (pages ou App Router)
- **React** 18+
- **Tailwind CSS** (ou autre framework CSS)
- **TypeScript** (optionnel, bonus)
- **React Hook Form** (ou gestion manuelle des formulaires)
- **Aucune API réelle** (données mockées)

---

## Fonctionnalités principales

1. **Page de connexion (Mock)**
   - Écran de connexion sans validation ni back-end
   - Design responsive

2. **Dashboard**
   - Barre de navigation (Dashboard, Clients, Ajouter un client)
   - Layout structuré

3. **Liste des clients**
   - Table affichant des clients mockés (JSON/Faker.js)
   - Colonnes : nom, email, téléphone, date de création
   - Tri par nom
   - Barre de recherche (filtre côté front)

4. **Fiche client**
   - Accessible via la table
   - Détails du client + historique d’activités (mocké)

5. **Formulaire d’ajout**
   - Champs : nom, prénom, email, téléphone (tous obligatoires)
   - Validation simple (email, téléphone)
   - Message de succès (pas de persistance)

---

## Roadmap & Logique de développement

### 1. Initialisation du projet
- Créer le repo Next.js (`npx create-next-app`)
- Installer Tailwind CSS
- Configurer la structure des dossiers (components, pages, mocks, etc.)

### 2. Authentification (Mock)
- Créer la page de connexion (`/login`)
- Rediriger vers le dashboard après "connexion"

### 3. Layout & Navigation
- Mettre en place un layout principal avec barre de navigation
- Créer les pages : Dashboard, Clients, Ajouter un client

### 4. Gestion des données mockées
- Générer une liste de clients mockés (JSON ou Faker.js)
- Stocker les données dans le state local ou context

### 5. Liste des clients
- Afficher la table des clients
- Ajouter tri et recherche

### 6. Fiche client
- Créer une page dynamique pour chaque client
- Afficher les détails et l’historique mocké

### 7. Formulaire d’ajout
- Créer le formulaire avec React Hook Form
- Ajouter la validation
- Afficher un message de succès
### 8. Bonus (si temps)
- Système de tags par client
- Pagination
- Responsive mobile complet
- Zustand/Redux Toolkit pour le state
- Tests (Jest, Testing Library)

---

## Logique générale

- **State management** : Utilisation du state local, context ou Zustand/Redux (bonus)
- **Navigation** : Next.js routing
- **Données** : Mockées, pas d’API réelle
- **UI** : Composants réutilisables, Tailwind CSS pour le style
- **Validation** : Simple, côté front

---

## Pour lancer le projet

```sh
npm install
npm run dev
```

---

## À faire

Voir [todo.md](todo.md)
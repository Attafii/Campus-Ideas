# Campus Ideas 

Campus Ideas est une application Angular moderne permettant aux étudiants et au personnel de proposer, consulter et gérer des suggestions d'amélioration pour la vie de campus.

##  Fonctionnalités

- ** Liste des suggestions** : Consultation de toutes les propositions avec leur statut.
- ** Recherche dynamique** : Filtrage en temps réel par titre ou catégorie.
- ** Systéme de Likes** : Soutenez les meilleures idées en un clic.
- ** Favoris** : Enregistrez vos suggestions préférées pour les retrouver facilement.
- ** Statuts visuels** : Suivi clair des propositions (Acceptée , En attente , Refusée ).
- ** Logique métier** : Les actions (Like/Favoris) sont désactivées pour les suggestions refusées.

##  Stack Technique

- **Framework** : Angular v19+
- **Langage** : TypeScript
- **Style** : CSS3 (Design moderne et responsive)
- **Data Binding** : Utilisation intensive de l'Interpolation, Property Binding, Event Binding et Two-way Binding.

##  Installation et Lancement

1. **Cloner le projet**
   ```bash
   git clone https://github.com/Attafii/Campus-Ideas.git
   cd Campus-Ideas
   ```

2. **Installer les dépendances**
   ```bash
   npm install
   ```

3. **Lancer le serveur de développement**
   ```bash
   npm start
   ```
   Rendez-vous sur `http://localhost:4200/`.

##  Structure du projet

- `src/app/core/header` : Barre de navigation supérieure.
- `src/app/core/footer` : Pied de page stylisé.
- `src/app/core/list-suggestion` : Composant principal gérant l'affichage et la logique des suggestions.
- `src/app/models/suggestion.ts` : Interface définissant la structure de données.


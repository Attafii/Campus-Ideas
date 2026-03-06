# Campus Ideas 

Campus Ideas est une application Angular moderne permettant aux �tudiants et au personnel de proposer, consulter et g�rer des suggestions d'am�lioration pour la vie de campus.

##  Fonctionnalit�s

- ** Liste des suggestions** : Consultation de toutes les propositions avec leur statut.
- ** Recherche dynamique** : Filtrage en temps r�el par titre ou cat�gorie.
- ** Syst�me de Likes** : Soutenez les meilleures id�es en un clic.
- ** Favoris** : Enregistrez vos suggestions pr�f�r�es pour les retrouver facilement.
- ** Statuts visuels** : Suivi clair des propositions (Accept�e , En attente , Refus�e ).
- ** Logique m�tier** : Les actions (Like/Favoris) sont d�sactiv�es pour les suggestions refus�es.

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

2. **Installer les d�pendances**
   ```bash
   npm install
   ```

3. **Lancer le serveur de d�veloppement**
   ```bash
   npm start
   ```
   Rendez-vous sur `http://localhost:4200/`.

##  Structure du projet

- `src/app/core/header` : Barre de navigation sup�rieure.
- `src/app/core/footer` : Pied de page stylis�.
- `src/app/core/list-suggestion` : Composant principal g�rant l'affichage et la logique des suggestions.
- `src/app/models/suggestion.ts` : Interface d�finissant la structure de donn�es.


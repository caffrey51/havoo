# HAVOO

Prototype V0 du tableau de bord familial HAVOO.

## Fonctionnalités V0

- Dashboard mural paysage responsive
- Profils Hugues, Caro, Sacha et Jules
- Agenda familial
- Tâches assignées
- Liste de courses
- Menu de la semaine
- Idées recettes
- Messages texte et vocaux
- Dictée vocale navigateur quand disponible
- PWA installable et cache hors-ligne
- Sauvegarde locale avec `localStorage`

## Tester

Le projet est une application web statique : `index.html`, `styles.css`, `app.js`. Pour les fonctions microphone/PWA, servir le projet en HTTPS ou sur localhost.

## Limite volontaire de la V0

Les données sont locales à chaque appareil. Il n'y a pas encore de synchronisation téléphone/tablette. La prochaine étape sera un backend partagé (par exemple Supabase) après validation de l'ergonomie.

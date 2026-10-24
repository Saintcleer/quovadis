# GuideLocal — prototype MVP

## Démarrer
1. Décompressez le dossier.
2. Ouvrez `index.html` dans un navigateur moderne.
3. Les données sont enregistrées dans le stockage local de ce navigateur.

## Fonctions présentes dans cette maquette
- Recherche par pays, ville, date, mode de déplacement, langue, statut du guide, spécialité et budget.
- Profils de démonstration avec tarifs, langues, spécialités et informations de véhicule fictives.
- Création/connexion de comptes locaux de démonstration.
- Création d'un profil guide et affichage dans la recherche.
- Création de demandes de réservation avec date, heure, durée, participants, mode et point de rendez-vous.
- Statuts de réservation et simulation de confirmation réciproque.
- Tableau de bord guide et écran d'administration de démonstration.
- Export JSON des données locales.

## Identifiants administrateur de démonstration
E-mail : `admin@demo.local`
Mot de passe : `admin123`

## Limites critiques
Ce projet est un prototype front-end, pas un service prêt pour des clients réels.
- Pas de serveur, base de données partagée ou authentification sécurisée.
- Les mots de passe de test sont conservés localement : n'utilisez aucun vrai mot de passe.
- Les codes de rencontre sont simulés et ne prouvent aucune identité.
- Aucun paiement, remboursement, SMS, e-mail, GPS temps réel ou vérification documentaire n'est intégré.
- Les profils, avis, prix et véhicules préchargés sont fictifs.
- L'écran administrateur est visible sans contrôle d'accès serveur.
- Les données peuvent être perdues si le stockage du navigateur est effacé.

## Étapes recommandées pour un vrai MVP
1. Choisir la stack serveur et héberger le projet sous HTTPS.
2. Ajouter une API et une base de données (comptes, guides, disponibilités, réservations, audit).
3. Mettre en place une authentification éprouvée, autorisations par rôle et récupération de compte.
4. Connecter un prestataire de vérification d'identité et traiter les documents de façon conforme.
5. Intégrer un prestataire de paiement compatible avec les pays cibles.
6. Ajouter notifications, cartographie, journalisation, sauvegardes et outils de support.
7. Effectuer tests de sécurité, tests utilisateurs et validation juridique locale avant lancement.

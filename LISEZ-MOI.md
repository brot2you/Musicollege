# Musicollège — première version

## Vision et écrans
Un studio musical pour écouter, expérimenter, créer et expliciter ses choix sans solfège préalable. Écrans : accueil et profil local ; carte de six missions ; fiche de mission ; carnet et badges ; sources et crédits. Séances proposées : 5 à 10 minutes.

## Programme et choix de progression
Vérification : 28 octobre 2026. Pour 2026-2027, Éduscol indique les programmes d'éducation musicale du BO n° 31 du 30 juillet 2020 : 6e en cycle 3 ; 5e, 4e et 3e en cycle 4. Les ressources d'accompagnement sont des aides et ne sont pas le programme réglementaire. L'application propose des activités adaptables à tous ces niveaux : il ne s'agit pas d'une progression officielle par classe.

- BO et annexes : https://www.education.gouv.fr/bo/20/Hebdo31/MENE2018714A.htm
- Cycle 3 : https://eduscol.education.gouv.fr/4356/enseigner-au-cycle-3
- Cycle 4 : https://eduscol.education.gouv.fr/4362/enseigner-au-cycle-4
- Ressources : https://eduscol.education.gouv.fr/4428/education-musicale

Les grandes entrées concernent la voix, l'écoute et la comparaison, l'exploration et la création, l'échange et l'argumentation. Ces six activités n'épuisent pas les programmes. Elles ont été conçues pour initier un travail à prolonger avec l'enseignant.

## Les six missions
Toutes : cycle 3 (6e) ou cycle 4 (5e–3e), aucun prérequis de notation musicale, aide par reformulation, exemple et indice ; réécoutes et essais libres ; référence BO ci-dessus. Les sons sont des signaux synthétiques originaux générés dans le navigateur, sans enregistrement ni interprète.

| Mission et consigne | Objectif et déroulement | Critère et validation | Badge |
|---|---|---|---|
| Le battement caché : choisir la piste à pulsation régulière | Comparer deux motifs synthétiques et distinguer pulsation et rythme ; réponse et retour explicatif | Choisir A ; correction automatique | Oreille curieuse |
| À toute allure ? : trouver le tempo le plus rapide | Comparer deux séries de battements | Choisir B ; correction automatique | Explorateur des tempos |
| Qui sonne comme ça ? : trouver le son rond et doux | Comparer deux sons synthétiques, sinusoïdal et carré ; ce ne sont pas des instruments | Choisir A ; correction automatique | Explorateur des timbres |
| Pareil ou différent ? : repérer le motif répété | Comparer deux séquences synthétiques | Choisir A ; correction automatique | Détective des motifs |
| Fabrique ta boucle : placer des sons et expliquer un choix | Créer et écouter 4 mesures de 4 temps sur 3 pistes ; expliquer l'organisation | Au moins un son et une courte explication ; trace enregistrée, autoévaluation, sans jugement artistique | Architecte du rythme |
| Une phrase, deux intentions : décrire une intention vocale | Dire ou imaginer une phrase et expliquer un choix de voix | Une courte explication ; autoévaluation ou discussion ; la pratique vocale n'est pas mesurée | Voix expressive |

Chaque activité terminée rapporte 20 points une fois. Les badges témoignent de la réalisation indiquée et ne prouvent pas la maîtrise d'une compétence. Un retour explicatif et un nouvel essai sont proposés aux questions. Pas de classement, pénalité, chronomètre ou achat. Toutes les activités restent accessibles. Le carnet invite à réactiver, mais ne met pas encore en œuvre de calendrier de révision espacée.

## Lancement
Décompresser le ZIP et ouvrir `index.html` dans un navigateur récent. Autoriser le son si le navigateur le demande. Aucun son ne démarre automatiquement. Un bouton arrête les sons, et un curseur règle le volume dans les activités sonores.

## GitHub Pages avec GitHub Desktop
1. Créer un dépôt GitHub, par exemple `Musicollege`, et le cloner avec GitHub Desktop.
2. Copier **le contenu du ZIP** à la racine du dossier du dépôt : `index.html`, `style.css`, `missions.js`, `app.js`, `LISEZ-MOI.md`.
3. Dans GitHub Desktop, saisir un résumé, cliquer sur « Commit to main » puis « Push origin ».
4. Dans GitHub, ouvrir Settings > Pages, choisir « Deploy from a branch », branche `main`, dossier `/ (root)`, puis enregistrer. L'adresse apparaîtra dans Pages après publication.

## Limites connues et suite
La sauvegarde utilise localStorage sur l'appareil et peut être effacée dans le carnet ; changer de navigateur ou d'appareil ne transfère rien. Pas de comptes, serveur, synchronisation, microphone ou mode classe. Le séquenceur joue quatre mesures une fois : pas d'export audio. L'écoute ne bénéficie pas d'une alternative équivalente pour toutes les compétences auditives ; la description visuelle change l'objectif évalué. Pas de mesure de rythme chronométrée ni de justesse vocale. Le projet de chanson collective, les ressources culturelles documentées, les personnalisations, le mode enseignant et une véritable réactivation espacée sont à développer. Pas de service worker ou de promesse de disponibilité hors ligne après installation. Avant utilisation auprès d'élèves : tester avec différents appareils et technologies d'assistance, réaliser une analyse des données et des risques et vérifier l'accessibilité ; aucune certification ni conformité RGPD n'est revendiquée.

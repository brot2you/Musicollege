# Musicollège v2 — ton studio musical

Application élève d'éducation musicale pour le collège (6e à 3e). Un seul fichier `index.html`, autonome (ES5, sans dépendance hormis Google Fonts, avec des polices de repli). Les données restent sur l'appareil (localStorage).

## Contenu
- **19 missions dans 6 studios**, couvrant les 4 compétences du programme (BO n° 31 du 30 juillet 2020, cycles 3 et 4).
  - Labo du rythme : pulsation, tempo, binaire et ternaire, ostinato.
  - Cabine d'écoute : hauteur, nuances, legato et staccato, timbres.
  - Salle des formes : répétition, variation et contraste ; formes AB, ABA et rondo ; monodie et canon ; majeur et mineur.
  - Studio voix : tessitures, « L'écho » (chant autoévalué), interprétation d'une phrase.
  - Atelier de création : séquenceur de batterie, mélodie pentatonique, export WAV.
  - Discothèque : reconnaissance des époques, critique argumentée avec repérage du vocabulaire.
- **Questions générées à chaque série** de 5, rejouables à l'infini. La difficulté s'adapte à la classe choisie.
- **Disque gagné** si au moins 4 réponses sur 5 sont trouvées du premier coup ; disque d'or pour 5 sur 5. Les récompenses restent dans l'appli : points, titres, collection.
- **Réactivation espacée** : une mission réussie revient après 2, 4, 7, 14 puis 30 jours.
- **Discothèque** de 10 époques, du Moyen Âge à l'électro. Chaque fiche contient un extrait joué par l'appli et un lien de recherche YouTube.
- **Lexique** de 52 termes, avec des exemples sonores.
- **Dessin des sons** : une partition graphique s'affiche après chaque réponse.
- **Mode classe** pour le vidéoprojecteur : sans points, réponse révélée par l'enseignant.
- **Carnet** : collection, compétences, traces écrites, impression, export et import (pour changer d'appareil).
- **Réglages** : police Lexend, texte agrandi, contraste renforcé, animations réduites.

## Sons et droits
Tous les sons sont synthétisés en direct (Web Audio API) : aucun fichier audio n'est fourni.
- Les mélodies sont des arrangements simplifiés d'œuvres du domaine public : grégorien, Greensleeves, Petzold, Mozart, Grieg, Satie, Joplin, Frère Jacques.
- Les rythmes rock, rap et électro sont des créations originales.
- Les liens YouTube sont des recherches, pas des vidéos précises.

## Déploiement avec GitHub Desktop
1. Copier `index.html`, `.nojekyll` et ce fichier à la racine du dépôt (par exemple `Musicollege`), en remplaçant les anciens `style.css`, `app.js` et `missions.js`, qu'il faut supprimer.
2. Faire un commit, puis cliquer sur Push origin.
3. Dans Settings > Pages, choisir la branche `main`, dossier `/ (root)`.

Les progressions de la v1 (clé `musicollege_v1`) sont reprises automatiquement.

## Limites connues
- **iPhone et iPad** : le son Web Audio est coupé si le bouton silencieux est activé. Aucun son ne démarre sans action de l'élève.
- **Pas de microphone** : la pratique vocale est autoévaluée.
- **Imitations simplifiées** : les instruments et les voix sont des imitations synthétiques basiques.
- **Sauvegarde locale** : elle dépend du navigateur. La navigation privée peut l'empêcher.
- **Conformité** : aucune conformité RGPD ni certification d'accessibilité n'est revendiquée. Testé dans Chromium (bureau et mobile en 390 px), pas encore sur appareil iOS réel.

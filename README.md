# TESTASSE

## Tête de lit à réduction active des nuisances sonores

TESTASSE est un projet open source expérimental visant à développer une tête de lit capable de réduire localement les nuisances sonores de basse et très basse fréquence autour de la zone de sommeil.

Le projet étudie notamment l'utilisation du contrôle actif du bruit (ANC), de capteurs acoustiques, d'un traitement numérique du signal (DSP), de transducteurs basse fréquence et de microphones d'erreur.

## Principe général

Architecture étudiée :

`bruit environnemental → capteur de référence → conditionnement/ADC → DSP ANC → DAC/amplification → transducteurs → zone locale autour de la tête → microphones d'erreur`

L'objectif est d'expérimenter une réduction locale du bruit, en particulier dans les basses fréquences, avec calibration adaptée à l'environnement acoustique.

## Organisation

- `hardware/` : mécanique, électronique, capteurs, amplificateurs et conception matérielle.
- `software/` : traitement DSP, ANC et calibration.
- `docs/` : architecture, calculs, simulations, antériorités et documentation technique.
- `tests/` : protocoles, mesures et résultats expérimentaux.

## Licence

Sauf mention contraire dans un fichier ou sous-dossier, les éléments originaux publiés dans ce dépôt sont mis à disposition sous licence MIT. Voir le fichier `LICENSE`.

La licence MIT permet notamment l'utilisation, la copie, la modification, la distribution et l'utilisation commerciale du contenu couvert par cette licence, sous réserve de conserver la notice de copyright et la notice de licence.

Les composants, bibliothèques, documents ou références provenant de tiers restent soumis à leurs propres licences et droits.

## État du projet

Projet de recherche et de prototypage. Les architectures, calculs et performances décrits peuvent évoluer à mesure des essais et mesures.

## Sécurité

TESTASSE n'est pas un dispositif médical et aucune revendication thérapeutique n'est formulée.

La réalisation d'un prototype peut mettre en jeu des amplificateurs de puissance, des tensions électriques, des niveaux acoustiques élevés, des excursions mécaniques importantes et des risques thermiques. Toute réalisation doit intégrer des protections appropriées et faire l'objet de validations électriques, mécaniques et acoustiques avant utilisation.

## Publication

Première publication publique du projet TESTASSE : septembre 2026.

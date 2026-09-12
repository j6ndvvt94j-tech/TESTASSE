# Architecture générale de TESTASSE

## Objectif

TESTASSE étudie la création d'une zone locale de réduction active des nuisances sonores autour de la tête d'une personne au repos.

## Chaîne fonctionnelle envisagée

1. Acquisition du bruit environnemental par un capteur de référence.
2. Conditionnement analogique et conversion analogique-numérique.
3. Traitement temps réel par DSP.
4. Algorithme adaptatif ANC, avec FxLMS multicanal comme piste de travail.
5. Conversion numérique-analogique et amplification.
6. Émission du signal de compensation par des transducteurs basse fréquence.
7. Mesure du résiduel acoustique par microphones d'erreur gauche et droit.
8. Adaptation continue et calibration de l'installation.

## Bande de travail

Le projet se concentre sur les basses et très basses fréquences. La zone 20–100 Hz constitue une cible pratique importante. L'extension sous 20 Hz reste expérimentale et impose des contraintes importantes de déplacement, puissance, structure et mesure.

## Calibration

La calibration automatique de la pièce et de la position d'écoute constitue un objectif important afin d'adapter les filtres et le contrôle aux caractéristiques acoustiques réelles de l'installation.

## Sécurité fonctionnelle

Le système devra notamment prévoir des limites de niveau, une surveillance de saturation et, lorsque cela est applicable, des protections thermiques et mécaniques. Une défaillance critique de la chaîne de mesure doit conduire à la désactivation du contrôle actif plutôt qu'à une émission non maîtrisée.

Ce document décrit une architecture de recherche et non un produit validé.

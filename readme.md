# Projet de pointeuse horaire

> Lucien LE FOLL - Datcha 2017

Arrivé à l'agence Datcha en septembre 2017, je consigne mes heures de présence au travail dans un document Excel, dans le but de garder une trace précise de ma présence. Le but de ce projet est de rassembler un maximum de données et de tester des solutions de visulisation qui soient innovantes, même pour un système aussi basique qu'une pointeuse.

## Source de données
Un tableau Excel contenant 5 colonnes :

- date
- heure d'arrivée
- heure de départ
- temps de pause (déjeuner, rigolade ...)
- présence totale (heure de départ - heure d'arrivée - temps de pause)

## Usages de la source
Plusieurs moyens peuvent être mis en place pour exploiter le tableau de données d'entrée :

- Script JS -> Intégré au sein d'un fichier HTML, et avec l'aide de librairies comme D3.js et Vue.js il est possible de mettre en exergue certaines constantes (heures moyennes d'arrivée et de départ, temps moyen passé au bureau ...)
- Application Electron -> A tester

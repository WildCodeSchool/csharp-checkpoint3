# Checkpoint3

## Objectifs

* Créer une API
* Effectuer des tests sur une API
* Créer une interface graphique avec XAML et WPF

## Le programme

Tu vas écrire un explorateur de fichier version microservice. Le programme est constitué de deux parties: un web service qui permet d'effectuer des opérations sur le disque dur et une interface graphique pour tester le web service.

### L'API

L'API met à disposition un point d'entrée qui accepte trois méthodes:
* GET **/file/{chemin vers un fichier}** - Affiche le contenu d'un fichier 
* DELETE **/file/{chemin vers un fichier}** - Supprime un fichier (attention avec celui-ci)
* PUT **/file/{chemin vers un fichier}** - Crée un fichier au chemin désiré 

### Tests fonctionnels

Crée une interface graphique qui permet de tester l'API.

Trois boutons testent chacune des méthodes du point d'entrée **/file**. Après l'appui sur le bouton, le résultat est affiché dans un champ de texte non éditable.

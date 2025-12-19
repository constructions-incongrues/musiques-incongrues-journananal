# Episodes du Zeitgeist

Ce dossier contient les épisodes publiés du Zeitgeist de Musiques Incongrues.

## Structure

Chaque épisode est composé de deux fichiers :
- `YYYY-MM-DD-titre.json` : Les données brutes du zeitgeist en format JSON
- `YYYY-MM-DD-titre.html` : La version HTML complète de l'épisode

## Format des noms de fichiers

Les fichiers suivent le format : `YYYY-MM-DD-titre-slug`

Exemple : `2025-12-19-zeitgeist-hebdomadaire.json` et `2025-12-19-zeitgeist-hebdomadaire.html`

## Publication

Les épisodes sont automatiquement publiés via le workflow n8n `zeitgeist.publish` depuis l'interface de prévisualisation.

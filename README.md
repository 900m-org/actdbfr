# JSON de Gestion de Tâches

Ce référentiel contient un fichier JSON de gestion de tâches, qui peut être utilisé pour stocker des informations sur différentes tâches, y compris leur titre, la durée estimée, le type et une brève description.

## Structure du JSON

Le fichier JSON est structuré de la manière suivante :

```json
{
  "posts": [
    {
      "id": 1,
      "title": "Titre de la tâche 1",
      "temps": "5",
      "type": "Participer",
      "description": "Description de la tâche 1"
    },
    {
      "id": 2,
      "title": "Titre de la tâche 2",
      "temps": "20",
      "type": "Entreprendre",
      "description": "Description de la tâche 2"
    },
    {
      "id": 3,
      "title": "Titre de la tâche 3",
      "temps": "45",
      "type": "Informer",
      "description": "Description de la tâche 3"
    }
  ]
} '''

Chaque tâche est représentée par un objet JSON dans le tableau "posts".
Chaque tâche a un identifiant unique ("id"), un titre, une durée estimée en minutes ("temps"), un type de tâche ("type") et une description.


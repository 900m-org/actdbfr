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
}
```

* Chaque tâche est représentée par un objet JSON dans le tableau "posts".
* Chaque tâche a un identifiant unique ("id"), un titre, une durée estimée en minutes ("temps"), un type de tâche ("type") et une description.

## Comment Contribuer

Si vous souhaitez contribuer à ce projet en ajoutant de nouvelles tâches par exemple une tache 4 : 

```json
    {
      "id": 4,
      "title": "Titre de la tâche 4",
      "temps": "23",
      "type": "Participer",
      "description": "Description de la tâche 4"
    },

```
Il suffit de rajouter la tache à la suite du JSON :

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
    },
    {
      "id": 4,
      "title": "Titre de la tâche 4",
      "temps": "23",
      "type": "Participer",
      "description": "Description de la tâche 4"
    }
  ]
}
```


# 900M

*(English below)*

## Avis aux contributeurs

Toutes les contributions soumises aux projets de cette organisation :

- sont soumises à la licence AGPL-3.0 ;
- sont soumises à la politique de contribution et de propriété intellectuelle de l'association 900m.

Veuillez lire l'intégralité de cette politique avant de contribuer :
https://github.com/900m-org/.github/blob/main/CONTRIBUTING.md


## Contributor Notice

All contributions submitted to projects of this organization:

- are licensed under AGPL-3.0;
- are subject to the contribution and intellectual property policy of the 900m Association.

Please read the complete policy before contributing:
https://github.com/900m-org/.github/blob/main/CONTRIBUTING.md

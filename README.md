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

Si vous souhaitez contribuer à ce projet en ajoutant de nouvelles tâches ou en apportant des modifications, voici les étapes à suivre :

1. Fork ce référentiel vers votre compte GitHub.
2. Clonez le référentiel forké sur votre machine locale :


git clone https://github.com/VOTRE_NOM_UTILISATEUR/fichier-json-gestion-de-taches.git


3. Apportez les modifications nécessaires au fichier JSON, en ajoutant de nouvelles tâches ou en modifiant les tâches existantes. Assurez-vous de suivre la structure JSON existante.
4. Committez et poussez vos modifications vers votre référentiel GitHub :


git commit -m "Ajout de nouvelles tâches" # Personnalisez votre message de commit
git push


5. Ouvrez une pull request (demande de fusion) vers le référentiel d'origine en expliquant vos modifications.

Votre demande de fusion sera examinée, et une fois acceptée, vos modifications seront intégrées dans le fichier JSON de gestion de tâches.

N'hésitez pas à ouvrir des issues pour discuter des modifications que vous souhaitez apporter ou pour signaler des problèmes. Vos contributions sont les bienvenues !

## Changelog

* 2023-07-20 : Initial release
* 2023-07-21 : Ajout de la documentation

## Licence

Ce projet est sous licence MIT.



# album
Returns an JSON object of all albums that the band has ever created.

## Base
```
https://api.unnecessarylibraries.com/imdragons/v1/public/album
```

## Path

| REQ | PATH           |
|-----|----------------|
| **GET** | /album/        |
| **GET** | /album/{id}    |
| **GET** | /album/{title} |

## Response Model
```json
{
    "id": number,
    "title": string,
    "length": number,
    "recorded": date,
    "label": [ strings ],
    "genre": [ strings ],
    "released": date,
    "producers": [ strings ],
    "tracks": [ strings ]
}
```

## Example Model
```json
{
    "id": "0",
    "title": "Night-Visions",
    "length": "42:10",
    "recorded": "2009 - July 2012",
    "label": [
        "Interscope",
        "KIDinaKORNER"
    ],
    "genre": [
        "Alternative rock",
        "Pop Rock",
        "Synth Rock",
        "Rock",
        "Synth Pop",
        "Pop"
    ],
    "released": "September 4, 2012",
    "producers": [
        "Alex Da Kid",
        "Brandon Darner"
    ],
    "tracks": [
        "Radioactive",
        "Tiptoe",
        "It's Time",
        "Demons",
        "On Top Of The World",
        "Amsterdam",
        "Hear Me",
        "Every Night",
        "Bleeding Out",
        "Underdog",
        "Nothing Left to Say"
    ]
},
```
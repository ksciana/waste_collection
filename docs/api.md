---
hide:
  - navigation
  - toc
---

# Rest API

Url to data
```
https://waste-collection.sciana.pro/api/v1/LOCATION_ID.json
```

## Example

fetch: https://waste-collection.sciana.pro/api/v1/3.json

result:
```json
{
    "data": {
        "id": "3",
        "name": "Bukówek, Cesarzowice, Chwalimierz, Ciechów, Ligotka, Michałów, Pęczków, Wrocisławice, Ogrodnica, Środa Śląska (ulice: Reymonta, Miłosza, Ogrodnicka)",
        "garbage_kinds": [
            {
                "name": "Papier",
                "disposals": [
                    { "date": "2026-01-13" },
                    { "date": "2026-02-10" },
                    { "date": "2026-03-10" },
                    { "date": "2026-04-14" },
                    { "date": "2026-05-12" },
                    { "date": "2026-06-09" }
                ]
            },
            {
                "name": "Szkło",
                "disposals": [
                    { "date": "2026-01-27" },
                    { "date": "2026-02-27" },
                    { "date": "2026-03-24" },
                    { "date": "2026-04-28" },
                    { "date": "2026-05-26" },
                    { "date": "2026-06-23" }
                ]
            },
...
```

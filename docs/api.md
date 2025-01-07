---
hide:
  - navigation
  - toc
---

# Rest API

Url to data
```
https://waste-collection.sciana.pro/data/v1/LOCATION_ID.json
```

## Example

fetch: https://waste-collection.sciana.pro/data/v1/3.json

result:
```json
{
    "region": {
        "id": "3",
        "name": "Bukówek, Cesarzowice, Chwalimierz, Ciechów, Ligotka, Michałów,  Pęczków,  Wrocisławice",
        "garbage_kinds": [
            {
                "name": "Papier",
                "disposals": [
                    { "date": "2025-01-28" },
                    { "date": "2025-02-18" },
                    { "date": "2025-03-18" }
                ]
            },
            {
                "name": "Szkło",
                "disposals": [
                    { "date": "2025-01-14" },
                    { "date": "2025-02-04" },
                    { "date": "2025-03-04" }
                ]
            },
...
```
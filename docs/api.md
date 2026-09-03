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

fetch: https://waste-collection.sciana.pro/api/v1/3brodnojson

result:
```json
{
    "data": {
        "id": "brodno",
        "name": "Brodno",
        "garbage_kinds": [
            {
                "name": "Papier zabudowa jednorodzinna",
                "disposals": [
                    { "date": "2026-09-09" },
                    { "date": "2026-10-07" },
                    { "date": "2026-11-04" },
                    { "date": "2026-12-02" }
                ]
            },
            {
                "name": "Papier zabudowa wielorodzinna",
                "disposals": [
                    { "date": "2026-09-09" },
                    { "date": "2026-09-26" },
                    { "date": "2026-10-07" },
                    { "date": "2026-10-24" },
                    { "date": "2026-11-04" },
                    { "date": "2026-11-21" },
                    { "date": "2026-12-02" },
                    { "date": "2026-12-19" }
                ]
            },
...
```

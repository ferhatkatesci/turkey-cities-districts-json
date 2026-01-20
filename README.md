# Turkey Cities and Districts JSON Data

A comprehensive and structured JSON dataset containing all cities and districts of Turkey, including regional info, plate codes, and phone area codes.

## Features

- **81 Cities:** Full list of Turkish cities.
- **973 Districts:** Detailed list of districts for every city.
- **Metadata:** Includes:
  - `plateCode`: Vehicle registration codes.
  - `phoneCode`: Area codes for landlines.
  - `region`: Geographical regions (e.g., Marmara, Akdeniz).
  - `slug`: URL-friendly names for web development.

### Example Snippet

```json
[
  {
    "id": 1,
    "name": "Adana",
    "slug": "adana",
    "region": "Akdeniz",
    "plateCode": "01",
    "phoneCode": "322",
    "districts": [
      {
        "id": 1,
        "name": "Aladağ",
        "slug": "aladag"
      },
      {
        "id": 2,
        "name": "Ceyhan",
        "slug": "ceyhan"
      }
    ]
  }
]
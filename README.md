# Swedish Counties and Municipalities JSON

This repository contains a JSON file with data on Swedish counties and municipalities. The data is based on information from [Statistics Sweden (SCB)](https://www.scb.se/hitta-statistik/regional-statistik-och-kartor/regionala-indelningar/lan-och-kommuner/lan-och-kommuner-i-kodnummerordning/).

## Svenska Län och Kommuner JSON

Detta repository innehåller en JSON-fil med data om svenska län och kommuner. Datan är baserad på information från [Statistiska Centralbyrån (SCB)](https://www.scb.se/hitta-statistik/regional-statistik-och-kartor/regionala-indelningar/lan-och-kommuner/lan-och-kommuner-i-kodnummerordning/).

## File Structure

- `kommuner.json`: Contains the list of counties and their respective municipalities in Sweden.

## Data Format

The JSON file is structured as follows:

- `code`: The code of the county or municipality.
- `name`: The name of the county or municipality.
- `municipalities`: A list of municipalities within the county, each with its own code, name, and short name.

Example:

```json
[
  {
    "code": "01",
    "name": "Stockholms län",
    "municipalities": [
      {
        "code": "0114",
        "name": "Upplands Väsby kommun",
        "shortName": "Upplands Väsby"
      },
      ...
    ]
  },
  ...
]
```

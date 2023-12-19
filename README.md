# Mein erstes API

## Allgemeine Infrastruktur
![](./images/Infrastructure.png)

## API Dokumentation
`GET /allitems`: Gibt Alle Elemente der Shopping Liste zurück

`GET /itembyid/{itemdId}`: Gibt ein einzelnes Elemnt zurück.
**Parameter**: `itemId` - Einzigartige Id des Elements

POST /api/new_element
Content-Type: application/json

{
  "name": "Beispiel",
  "description": "Ein Beispiel-Element"
}

DELETE /api/delete_element/123

PUT /api/update_element/123
Content-Type: application/json

{
  "name": "Neuer Name",
  "description": "Aktualisierte Beschreibung"
}


 

FORMAT: 1A

# Vegetable API stub
vegetables!

## Data Structures
### Vegetable
+ name: eggplant (required)
+ color (string, required)

## Vegetables [/vegetables]
### Get all vegetables [GET]
+ Response 200 (application/json)
  + Attributes (array[Vegetable])

### add a vegetable [POST]
+ Request (application/json)
  + Attributes (Vegetable)
+ Response 201


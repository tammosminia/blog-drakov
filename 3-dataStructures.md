FORMAT: 1A

# Vegetable API stub
data structures

## Data Structures
### Vegetable
+ name: eggplant (string, required)
+ color: purple (string)

## Vegetables [/vegetables]
### Get all vegetables [GET]
+ Response 200 (application/json)
  + Attributes (array[Vegetable])

### add a vegetable [POST]
+ Request (application/json)
  + Attributes (Vegetable)
+ Response 201

## one vegetable [/vegetables/{name}]
### Get one vegetable [GET]
+ Response 200 (application/json)
  + Attributes (Vegetable)


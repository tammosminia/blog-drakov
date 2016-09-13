FORMAT: 1A

# Vegetable API stub
gets

## Root [/]
### Documentation [GET]
+ Response 200 (text/plain)
This is an API about vegetables.
With examples about how to get them.

## Vegetables [/vegetables]
### Get all vegetables [GET]
+ Response 200 (application/json)
[
    {
        "name": "eggplant",
        "color": "purple"
    },
    {
        "name": "broccoli",
        "color": "green"
    }
]

## one vegetable [/vegetables/{name}]
### Get one vegetable [GET]
+ Response 200 (application/json)
{
    "name": "eggplant",
    "color": "purple"
}




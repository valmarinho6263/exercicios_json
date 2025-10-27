1-
```
[
    {"id": 1, "name": "keyboard","price": 49.9},
    {"id": 2, "name": "Mouse", "price" : 29.9},
    {"id": 3, "name": "Monitor", "price": 899.0},
    {"id": 4, "name": "Headset", "price" :199.0}
]
```
---
2-
```
[
    {
        "id": 1,
        "name": "keyboard",
        "price": 49.9
    },
    {
        "id": 2,
        "name": "Mouse",
        "price": 29.9
    },
    {
        "id": 3,
        "name": "Monitor",
        "price": 899
    },
    {
        "id": 4,
        "name": "Headset",
        "price": 199
    }
]
```
---
3-
```
JSON.parse(JSON.stringify(orders))
```
---
4-
```
const text = JSON.stringify(orders, null,2);
console.log(text);
```
---
5-
```
console.table(orders)
```
---
6-
```
console.table(orders, ["customer"]);
```



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

---
7-
```
const recentOrders = orders.filter(o => o.orderId >2);
console.table(recentOrders);
```
8-
```
{
    "theme ": "dark",
    "language ": "pt-BR",
    "notifications": true
}
```
9-
```
const profile = {name : Val Marinho",
                 age : 63,
                 city:"Goiania",
skills:["html", "css","js"] };
```
10-
```
{
  "name":"val",
  "age":63, 
  "city":"Goiania",
  "skills":["js", "react", "html"]
};
```
11
```
{
    "store": "TechShop",
    "items": [
        {
            "sku": "A123",
            "name": "Laptop",
            "Price": 2999,
            "tags": [
                "eletronics",
                "portable"
            ]
        },
        {
            "sku": "B456",
            "name": "mouse",
            "price": 99
        }
    ]
}
```
12
```
{
  "name":"val",
  "age" : 63,
"city" : " Goiania",}

{
 "name":"val",
  "age" : 63,
"city" : " Goiania"}
```
13
```
{
 'store': 'TechShop',
    'items': [
        {
            'sku': 'A123',
            'name': 'Laptop',
            'Price': 2999 },
        {
            'sku': 'B456',
            'name': 'mouse',
            'price': 99
        }
    ]
}

{
 "store": "TechShop",
    "items": [
        {
            "sku": "A123",
            "name": "Laptop",
            "Price": 2999 },
        {
            "sku": "B456",
            "name": "mouse",
            "price": 99
        }
    ]
}

```
14
```

{
  name : val,
  age  : 63,
 city :  Goiania,}

{
 "name":"val",
  "age" : 63,
"city" : " Goiania",}
```
15
```
const payments =[
                    {paymentId : 1, customer: "Ayla", amount : 250},
                   {paymentId  : 2, customer : "Elis", amount : 510},
                    {paymentId : 3, customer : "Maria", amount : 178},
                    {paymentId : 4, customer : "Heitor", amount : 89},
                   {paymentId : 5, customer : "Val", amount : 340}],

[
                  { "paymentId" : 1 ,"customer": "Ayla", "amount" : 250},
                  { "paymentId" : 2, "customer": "Elis", "amount" : 510},
                  { "paymentId": 3, "customer": "Maria", "amount" : 178},
                  { "paymentId": 4, "customer": "Heitor", "amount" : 89},
                  { "paymentId": 5, "customer": "Val", "amount" : 340}
];

```
16

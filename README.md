# SDA_LAB_5
RABBITMQ Implementation using nodejs

How to use

npm install inside two services

node server.js in two services

Run Rabbitmq on docker

First Send Post request on http://localhost:8082/ with
{
    "name": "burger",
    "availableQty": 5,
    "price": 2.23
}
You will get an Id in return
Copy that id
then send Post Request on http://localhost:8081/order/bismillah with
{
"name" : "burger",
"qty" : 6,
"price" : 500,
"productId": //copied Product Id
}


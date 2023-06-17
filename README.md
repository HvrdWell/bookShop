# BookShop backend

Complete demo project for yandex using spring-boot-starter-web, junit, slf4j & logback.

## Environment variables:

- `PORT`=8080

## Files in project:

log.json - file with logs
data.json - file with data about users and books

## Commands

curl -X GET 'http://localhost:8080/'

curl -X GET 'http://localhost:8080/allbooks'

curl -X GET 'http://localhost:8080/addNewBook' 

curl -X GET 'http://localhost:8080/account' 

curl -X POST 'http://localhost:8080/deleteBook' 

curl -X POST 'http://localhost:8080/addNewBook' 

curl -X GET 'http://localhost:8080/account/balance' -H 'Content-Type: application/json'

curl -X POST 'http://localhost:8080/market/deal' \
-H 'Content-Type: application/json' \
-d '{"id": 0, "amount": 2}'

###### End thx

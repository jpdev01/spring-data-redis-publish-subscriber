# spring-data-redis

# Pub Sub events with Redis

```
curl --request POST \
--url http://localhost:9292/publish \
--header 'Content-Type: application/json' \
--data '{
"id":1,
"name":"bag",
"qty":1,
"price":599
}'
```
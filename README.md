# sample-service
Openapi-rpc-node based sample microservice

# How to 

* Install dependencies:
    npm install

* Run service:
   npm start

* Hit test api:

  curl --location --request POST 'http://localhost:1002/sample-service/testApi?client_id=sample-service' \
  --header 'Content-Type: application/json' \
  --data-raw '{}'
# Go-Nats-Endpointless-Microservices-Communication  
This is the repository of building example app architecture for testing NATS.io Request&Reply methodology with single `docker-compose up -d` command.

# For Test App Request these endpoints
GET: http://localhost:9090/encrypt/Hello World!

The decrypted message is obtained by giving the jwt token generated by this request to the auth token in the request below.

GET: http://localhost:9090/decrypt
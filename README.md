# HPE_microservices
This exercise tries to develop an e-commerce system where a user can order an item and then view the progress of their order as it is fulfilled.

The e-commerce system will be having the following components:
* A container providing a REST interface that a user can use to place orders, and query the status of their orders.
* A container that handles the business logic of the application, including communication with the database. It will communicate with other containers via gRPC.
* A container that acts as a simulation of the warehouse, which asynchronously handles orders placed on the order queue via Kafka, and provides updates on the status of those orders.
* A CLI for use by support personnel to inspect the state of the system.
* A simple overview of the solution is presented in the below diagram.

A simple overview of the solution is presented in the below diagram.

![Screenshot 2024-06-03 at 10 51 22](https://github.com/katterianjali/HPE_microservices/assets/108899982/c00f97d6-a87d-41d1-bf34-dd41f983b0be)

# Glossary
TODO:

- REST
- gRPC
- Kafka
- CLI
- CI/CD
- DSCC
- Docker
- Kubernetes
- CDS
- PostgreSQL

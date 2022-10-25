# order-shop-config
The order shop gitops repo

This repo contains the arogcd CRD required to run the order shop demo

The demo contains: 

an application that receive oreders from the user and send it over a kafka topic
a kafka instance to process the orders
an application that reads the order from kakfka and store it to a database. This application aldo expose an endpoint to retrieve the order received.

This is the architecture diagrama

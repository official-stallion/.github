**Stallion** is a Message Broker that is implemented with **Go programming language**. You can use **Stallion** to publish events on 
specific topics and consume them over client side with SDKs. Stallion provides authentication so you can authorise your clients.

One good thing about **Stallion** is that it uses only Golang internal modules and has no external modules. Everything in **Stallion** is
pure Golang.

It comes with _Load Test_ (Race) and _Blackbox Exporter_ (Vet) to analyse the **Stallion** server.

## Features

| Feature      | Description                                | Version      |
| ------------ | ------------------------------------------ | -------------|
| Docker Image | Docker image for starting stallion server. | ```v0.1.1``` |
| Auth         | Authorising stallion users.                | ```v1.1.0``` |
| Mock         | Add mock server for unit tests.            | ```v1.1.2``` |
| Load Test    | Testing Stallion server under load.        | ```v1.2.2``` |
| Monitorig    | Blackbox exporter for stallion server.     | ```v1.2.2``` |

# Helm Charts for Rook Operator and Cassandra Cluster

Apache Cassandra is an opensource nosql distributed database used by multiple developers and companies. It provides easy scalability, high availability without compromising performance and proven fault-tolerance.
Rook orchestrates multiple storage solutions, each with a specialized Kubernetes Operator to automate management. Rook has an operator for cassandra providing similar orchestration functionality.

This repo contains the helm charts for both rook operator and cassandra cluster.


# How to Deploy

Helm Repo URL : https://platform9.github.io/rook-casandra-hack14
Add this repo to the repositories via Pf9 UI "Repositories" section.

* Deploy Rook Operator

     Select "rook-cassandra-operator" app and click "Deploy"

* Deploy Cassandra Cluster

     Select "rook-cassandra" app and click "Deploy"

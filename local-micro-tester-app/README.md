# local-micro-tester-app

## Description

This application is a Proof of Concept. 

Its goal is to serve as a testing framework for the interaction between different microservices within a company. 

It allows listing the applications from the Docker registry and deploying them in Docker.

This deployment is orchestrated through Nomad, and the service discovery is got with Consul.

It is thought to be used in local environments through the usage of a virtual machine, where the Docker registry, Nomad and Consul will be deployed.

## Run it

For running this project, you need to have a virtual machine with Docker, Nomad and Consul installed on it

Then build in your local machine (outside the virtual machine) this project using gradle and run the Springboot project
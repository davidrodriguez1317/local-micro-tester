# local-micro-tester
Proof of concept projects for a web application that tests microservices in local environment

It is composed by:

- local-micro-tester-app: the POC itself, a web application that will take a list of microservices from a Docker registry and then deploy them. The deployment takes place in a virtual machine that has to be created beforehand, and needs Consul and Nomad installed on it.
- delivery-cost-mock-app: mock application for testing the POC
- price-calculator-mock-app: mock application for testing the POC
- product-cost-mock-app: mock application for testing the POC
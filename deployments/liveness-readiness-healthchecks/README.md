# Liveness and Readiness Healthchecks Deployment

This example uses the [dfreilich/goflake-server](https://hub.docker.com/r/dfreilich/goflake-server) image, deploying it as a Pod, together with a service to access it. 
We will deploy 2 pods:
* One which works
* One which is failing a readiness check, by giving a 500 error

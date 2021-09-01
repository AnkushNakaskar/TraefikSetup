# TraefikSetup
This project explain the traefik setup
* Traefik is used to route the traffic to particular services from backend.
* You can define the rules for that, please check the whoim service in docker-componse.yml.
* Traefik can be configured with service provider like docker ,marathon, consul etc. By using those provider, it detect the scale.

# CMDs to test the scenario
* docker-compose up -d reverse-proxy
* docker-compose up -d whoami
* docker-compose up -d --scale whoami=2

# Import json into postman and check the API for invoke
# URLS
 * http://localhost:8080/dashboard/#/
 * http://127.0.0.1:8080/api/rawdata

# Reference 
  * https://doc.traefik.io/traefik/getting-started/quick-start/
  

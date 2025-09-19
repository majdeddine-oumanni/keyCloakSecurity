# code to install keyckloak server in docker
```
docker run -p 127.0.0.1:9090:8080 -e KC_BOOTSTRAP_ADMIN_USERNAME=admin -e KC_BOOTSTRAP_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:26.3.4 start-dev
```
the port is 9090 and the username is admin and password is admin
#

## name of the realm:
``
springboot-microservice-realm
``


## Client Name:
``
microservice-auth
``


## Client Secret:
``
hcLDb0JaVVE5Aq2zoB2XWOaSp2zLc1yH
``

## issuer: 
``
http://localhost:9090/realms/master
``

## token-endpoint
``
http://localhost:9090/realms/master/protocol/openid-connect/token
``
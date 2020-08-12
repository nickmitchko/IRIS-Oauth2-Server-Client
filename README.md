# IRIS-Oauth2-Server-Client with Apache
Sample of an Oauth2/OpenId Server and Client with IRIS for Health instead of iris-community.

## Setup 

1. Clone repo
```bash
mkdir ~/oauth-demo
git clone https://github.com/nickmitchko/IRIS-Oauth2-Server-Client.git ~/oauth-demo
```
2. Copy your iris.key to the folder you clone this repository to the directory you clone this demo
3. Change the iris for health image (as required) in the docker-compose.yml file (if required).

## Run
```
docker-compose up --build
```

## Using OAuth

Got to https://localhost/csp/myclient/Web.OAUTH2.Cache1N.cls
Login : SuperUser/password


#Keycloak (on Docker)

(https://www.keycloak.org/getting-started/getting-started-docker)
docker run -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin quay.io/keycloak/keycloak:13.0.1

http://localhost:8080

admin
admin

go mod init github.com/jdoliveirasa/keycloak-goclient

go run main.go
http://localhost:8081

Keycloak (TRABALHANDO COM TEMAS)

docker-compose up -d --build
docker rm -f $(docker ps -q -a)
docker exec -it keycloak bash

cd /opt/jboss/keycloak/themes/

docker-compose stop app
docker-compose start app

keycloak-goclient

go get github.com/coreos/go-oidc/v3/oidc

go get github.com/coreos/go-oidc

go get -t github.com/coreos/go-oidc

go get Failed to run
go get -v golang.org/x/oauth2

go install github.com/coreos/go-oidc

go get github.com/coreos/go-oidc/v3/oidc

go install golang.org/x/oauth2

main.go:5:2: no required module provides package github.com/coreos/go-oidc; to add it:
        go get github.com/coreos/go-oidc
main.go:6:2: no required module provides package golang.org/x/oauth2; to add it:
        go get golang.org/x/oauth2
jonathan@EXTBP010101:~/keycloak-go

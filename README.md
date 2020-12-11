# GoRelated..
 - https://www.udemy.com/course/golang-how-to-design-and-build-rest-microservices-in-go/    course for go microservices development.
 - https://www.udemy.com/course/go-the-complete-developers-guide/     complete developer guide
 - https://github.com/traefik/traefik   Go Apigateway Lib <- Use this!

 - go tour https://tour.golang.org/basics/8
 - Building MicroService with Go: https://www.youtube.com/watch?v=eBeqtmrvVpg&t=215s
 - Api design guidance from MicroSoft:https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design
 - validate Lib:https://github.com/go-playground/validator
 - Gzip compression.
 - service registry and find etcd consul mdns kube-DNS
 - go watch:gowatch is a command line tool that builds and (re)starts your go project everytime you save a Go or template file.      https://github.com/silenceper/gowatch
 - graphPl using Go
 - Read YAML file etc:https://github.com/spf13/viper
## Project Layout
 - api:Stores the versions of the APIs swagger files and also the proto and pb files for the gRPC protobuf interface
 - cmd:This will contain the entry point[main.go]files for all the services and also anyother container images if any
 - config: All the sample files or any specific configuration files should be stored here
 - deploy: This directory will contain the deployment files used to deploy the application
 - internal: This package is the conventional internal package identified by the Go compiler. It contains all the packages which need to be private and imported by its child directories and immediate parent directory. All the packages from this directory are common across the project
 - pkg: This directory will have the complete executing code of all the services in separate packages.
 - tests: It will have all the integration and E2E tests
 - vendor: This directory stores all the third-party dependencies locally so that the version doesn’t mismatch later
 - configure aws Credentials https://www.youtube.com/watch?v=SON8sY1iOBU
 
### Project structure
https://dev.to/bastianrob/golang-microservices-and-monorepo-gp3
 ### https://www.velotio.com/engineering-blog/build-a-containerized-microservice-in-golang
 ### example:https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql
 ### Go Iris project example -
 
# dota2 related
- https://wikiwiki.jp/dota2/
- 

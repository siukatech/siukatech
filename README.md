Hello, I am siukatech (Karl), a system analyst based in Hong Kong.  
My main focus is backend, but I am also working in some frontend and devops studies and poc.    

I try to group the repositories into 3 categories.  
- DevOps
- Backend
- Frontend


====================================================================


# DevOps

## dev-env-set-up ([link](https://github.com/siukatech/dev-env-set-up))
<!--
### dev-env-set-up ([link](../../../dev-env-set-up))
-->  
docker-compose collection for dev


### Kafka
- Full Set-up Article ([link](https://github.com/siukatech/dev-env-set-up/kafka/README.md))
- Ssl Certificate ([link](https://github.com/siukatech/dev-env-set-up/kafka/README.md#01-ssl-certificate))
- Confluentinc Kafka ([link](https://github.com/siukatech/dev-env-set-up/kafka/README.md#11-confluentinc-kafka))
- ~~Wurstmeister Kafka ([link](https://github.com/siukatech/dev-env-set-up/kafka/README.md#21-wurstmeister-kafka))~~
- Akhq ([link](https://github.com/siukatech/dev-env-set-up/kafka/README.md#31-akhq))


## poc-jenkins-groovy-library-script ([link](https://github.com/siukatech/poc-jenkins-groovy-library-script))
A poc of using `jenkins`'s `groovy-libraries`.  


## rebase-child-interactively ([link](https://github.com/siukatech/rebase-child-interactively))
A project to test the `git` rebase.  


## rebase-current-changes-onto-branch ([link](https://github.com/siukatech/rebase-current-changes-onto-branch))
A project to test the `git` rebase `onto`.  



# Backend

## poc-react-backend-core ([link](https://github.com/siukatech/poc-react-backend-core))
A lib-project for other microservices (ms-project) to import.  
OAuth2 is integrated for the SSO with Keycloak as the development identity provider (IdP) server.  
`End-to-End-Encryption` (E2EE) is also introduced in this project.  


## poc-react-backend-app ([link](https://github.com/siukatech/poc-react-backend-app))
A ms-project imports the `react-backend-core` library which mainly focusing on the business logic and flow.  
OAuth2, end-to-end-encryption and others are taking care by the `react-backend-core` library.  


## poc-react-backend-user ([link](https://github.com/siukatech/poc-react-backend-user))
A ms-project imports the `react-backend-core` library as `user-service` to provide the permission information to other microservices.  


## openapi-spec ([link](https://github.com/siukatech/openapi-spec))
A poc project to test `openapi-specification`.  

### openapi-generator-example ([link](https://github.com/siukatech/openapi-spec/tree/main/openapi-generator-example))
Test openapi spec referencing other `yaml` / `json` files.  


## poc-openapi-generator-example ([link](https://github.com/siukatech/poc-openapi-generator-example))
A ms-project uses the openapi spec, from `openapi-spec`, to generate the `model` and `api` classes.  


## poc-cucumber-gherkin ([link](https://github.com/siukatech/poc-cucumber-gherkin))
A poc of `cucumber` and `gherkin`.  


## poc-spring-security-demo ([link](https://github.com/siukatech/poc-spring-security-demo))
A demo of `spring-security` with unit tests.  


## poc-oauth-client ([link](https://github.com/siukatech/poc-oauth-client))
A poc of following items.  
- spring oauth2-client ([link](https://github.com/siukatech/poc-oauth-client/tree/main/src))
- keycloak ([link](https://github.com/siukatech/poc-oauth-client#keycloak))
- postman ([link](https://github.com/siukatech/poc-oauth-client#postman))
- gradle bootRun ([link](https://github.com/siukatech/poc-oauth-client#gradle))


## poc-react-backend-plugin ([link](https://github.com/siukatech/poc-react-backend-plugin))
A `gradle custom plugin` project with `spring-boot` and `openapi-generator` integrations.  


## poc-gradle-plugin-consumer ([link](https://github.com/siukatech/poc-gradle-plugin-consumer))
A consumer project to use the `gradle custom plugin` (`react-backend-plugin`).  


## poc-react-backend-archetype ([link](https://github.com/siukatech/poc-react-backend-archetype))
An `archetype` project to generate maven ms-project with importing the `OAuth2`, `end-to-end-encryption` and other features that are taking care by the `react-backend-parent` library.  


## poc-dgs-demo ([link](https://github.com/siukatech/poc-dgs-demo))
Original dgs demo.  
- dgs: Domain Graph Service



# Frontend

## poc-react-frontend-app (branch: poc-mui-material-ts) ([link](https://github.com/siukatech/poc-react-frontend-app/tree/poc-mui-material-ts))
A poc to test react as `frontend` application.  


## poc-npm-test-package ([link](https://github.com/siukatech/poc-npm-test-package))
A poc of testing `npm`.  





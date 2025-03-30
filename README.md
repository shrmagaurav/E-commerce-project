Its a Micro Service architecture ecommerce platform to illustrate and maintain security of users with jwt tokens in user browser cookies
this project contains multiple microservices like customer-core that is responsible for managing customer data into a mysql database with encrypted id and salted hashed password
template service is responsible to show gui using thymeleaf (no need to implement frontend service) so that you can manage all the gui and route related work with this service
identity service is responsible to verify user from customer core if exist it will give the token to authenticate over all api's of all services

In order to run this application:
its already bind with ports 
clone all the services and run all of them seperately and hit the url in the browser localhost:8080/login

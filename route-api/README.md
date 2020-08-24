# RouteAPI
This Route API determines if two cities are connected the API should return 'yes' otherwise 'no'.

## Overview  
This Route API was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project. This is an example of building a swagger-enabled server in Java using the SpringBoot framework. The underlying library integrating swagger to SpringBoot is [springfox](https://github.com/springfox/springfox)  

## Running the Route API 
java -jar route-api-0.0.1-SNAPSHOT.jar

## API documentation
You can view the API documentation in swagger-ui by pointing to  
http://localhost:8080/swagger-ui.html

### Route API Resource URLS
* Is two cities connected?:
    * GET http://localhost:8080/connected?origin=Boston&destination=Newark


### Example
http://localhost:8080/connected?origin=Boston&destination=Newark

Should return yes

http://localhost:8080/connected?origin=Boston&destination=Philadelphia

Should return yes

http://localhost:8080/connected?origin=Philadelphia&destination=Albany

Should return no
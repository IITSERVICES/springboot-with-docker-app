- Let follow the below steps to execute the code:
- Step1:
  
   - Create the jar file for the project :
     
      ``` mvn clean install ```
   - Open the Docker Desktop
     
   -  Create the Docker Image
 
       ``` docker build -t spring-docker-demo:0.0.1 . ```
  -  Now go for docker compose
    
     ``` docker-compose up ```

- Step2: Open the postman and test the following url:

    - POST : http://localhost:2222/users
      ```
             {
              "name":"imtiaz",
              "email":"imtiaz@gmail.com"
             }
      ```
    - GET : http://localhost:2222/users



------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


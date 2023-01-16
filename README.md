### This project is a requirement to grant finish of module 04 (Domain, ORM and authorizations) from Backend (Spring Boot) course from https://devsuperior.com.br/

The following tasks were required to resolve the challenge:
* Implement the proposed conceptual model, with database seed.
* Add exceptions, validation, and security infrastructure to the design (OAuth2 wiht JWT token & refresh token).
* Implement the endpoint shown below.
    
    GET /users/profile (must show ONLY the data from authenticated user)
    
    
 The conceptual model is shown below:
 
 ![](https://rgiovann.github.io/image-repo/bds_05_concept.jpg)
    
The project was developed using ___TDD___ (*Test Driven Development*) methodology, Junit test cases are implemented in the following files (src/test/java):

-   _UserControllerIT.java_
-   _GenreTests.java_
-   _MovieTests.java_
-   _ReviewTests.java_
-   _UserTests.java_
-   _RoleTests.java_

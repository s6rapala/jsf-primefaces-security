# jsf-primefaces-spring-security

1. Checkout the source from the repository.
2. Open Eclipse. File->Import->Import Existing Maven Projects.
3. Point the root directory to checked out directory.
4. After importing the project, right click the project -> Run as -> Run Configurations -> Double Click on Maven Build.
5. Point the base directory to the project in the workspace.
6. In goals mention, spring-boot:run
7. Click Run
8. Open the Browser, got to http://127.0.0.1:8080/login.xhtml
9. A UI based on PrimeFaces is created. 
10. For username, enter 'raghu.palakodety' and password '1234' and it has a ROLE which is USER_ROLE.
11. For username, enter 'root' and password '5678' and it has an ADMIN_ROLE.

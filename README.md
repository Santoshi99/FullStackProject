# FullStackProject
1. Introduction:
    Designed an e-commerce website homepage to offer customers online shopping experience for home decoration products which allows customer to effortlessly navigate
through wide range of products with filters based on the top rated choices, preferred brands and specific categories which provides efficient shopping journey.

2. Functional Requirements:
IDE             : Eclipse, Visual StudioCode
API Testing     : PostMan
Database Tool   : MySQL workbench
FrameWorks      : SpringBoot, ReactJS
Languages       : Java 11
Database        : SQL, RDBMS 

3. Backend(SpringBoot Functionalities):

SpringBoot is a framework that simplifies development of Java applications with below features
AutoConfigurations: Implemented using Annotation-based Configurations
   Automatically configues defined beans based on the annotations applied to classes based on @Service, @Component, @Controller and @Repository etc

SpringBoot Starters :
   1. SpringBoot JPA: Helps in creating entity classes, CRUD repository helps in writing custom methods and queries for querying databases
   2. SpringBoot Security : 
        Security for users built using Json WebToken-based Authentication where user will be logged-in until the token expires.
        A JWT token will be created with encrpted values of username, password and a secret_key provided in the logic.
   3. SpringBoot logging : Logging of Info/Error using LogBack. 
   
SpringBoot CLI: Used to create spring boot project helps to maintain project structure when added required springboot dependencies.

Embedded Servers: 
    Used Tomcat server to connect client and server to connect frontend calls with backend to fetch the details.

Tables Used - Products, Users, Ratings, Categories

Rest API's:
1) Fetch products by category when click on NavBar implemeted using paging and sorting mechanism
2) JWT-Authentication based User SignIn and Registration 
3) Products Create, Delete and Update using CRUD operations.
4) Fetch products from Top ratings on page load 
5) Search products using keywords from title and description
6) Fetch Top branded products on page Load

Layers:
RestController(Presentation Layer)
Service(Business Layer)
Repository(persistent layer)
Database(DAO and Model classes)

FrontEnd (ReactJS):
React helpful in creating components and rendering components to the DOM which are reusable.
React Props/Hooks/Routers and Reducers helps dynamically change the content of the HTML DOM by changing states, passing props to change the components contents 
calling actions using Get/Post axios calls to backend and reduce the actions based on success/failure responses.


<img width="640" alt="1000062175" src="https://github.com/Santoshi99/FullStackProject/assets/47233668/ef405fba-92d3-4003-aad2-3ad750996503">
<img width="640" alt="1000062176" src="https://github.com/Santoshi99/FullStackProject/assets/47233668/874673a3-3183-4621-9461-cf3d9f4c8ac3">
<img width="640" alt="1000062173" src="https://github.com/Santoshi99/FullStackProject/assets/47233668/5046445c-8266-4843-8d62-29da29cf6ba6">
<img width="640" alt="1000062174" src="https://github.com/Santoshi99/FullStackProject/assets/47233668/0255317d-2690-4577-9a19-53b14115c25d">

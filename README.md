# SPRINGBOOT
In this we are going to learn about Spring Boot
" So normally in java we are creating object Manually. But in the spring we can give intruction to IOC(Inversion of Control where so many objects are present) and it can make oject for us.
- Application Context : Application context is the way to implement the IOC container. Actullay the IOC container and the Application context both are same. It is like the big box that can contain lots of objects.

IOC will scan all the classes and do the below check.
Note: If any class has annonation of "@component" then the IOC will keep it in the box. 
- Annotation is providing the information about the (class, interface, method, field).
- IN Spring Object is known as "bean".

  SpringBoot Annotation application can do the work of three annotation
  - @Configuration 
  - @EnableAutoConfiguration
  - @ComponentScan (Scan weather the the class will contain@component or not ?)
Note: we can also make the bean using @bean as well but it will only implement on the function.

@RestControllar is also do the same "making beans" but also do something else.
@AutoWired is use to borrow the object from the Spring and this is also called the dependency injection.

**************************************************** MAKING REST API USING SPRING *************************************************
- DO THE NECESSARY STEPS USING SPRING INITIALISER
- DOWNLOAD THE ZIP FILE
- EXTRACT THE FILE
- OPEN THE FOLDER IN THE IDE

REST API: REPRESENTABLE STATE TRANSFER. and the API (Application Programming Interface). 
Ok so lets imagine an Senario: You wnat to open the netflix. So you are the user of netflix and using the Rest API your phone/device can able to intreact with Netflix server. Your device is sending request and the server is giving response in return.
So how we can access the server using URL(172.17.18.19.8081/netflix/plans). Only with URL we are not able to access but we also need http verb.
There are mainly 4 http verb:
- GET (to see)
- PUT (to modify)
- POST (to create new)
- DELETE (to delete)

Whenever you are making controller making of one healthcare controller for checking. Now we will use @getmapping("health-check) of the following method. Now use the Postman to see weather te rest api will hit or not.
So if we can put @Requestmapping("./journal") on the class. it will map all the function inside it. ./jounal/abc and all the other as well.
Note: Method inside Controller class will be public so that it can access by the spring framework and other http request.

We can use both GET and POST.In the postman we can put some data in body > raw in JASOn format. To access that data we will use @Requestbody (Which means we can say spring to take data from the the request body and turn it into Java object that I can use it in code).







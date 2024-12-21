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



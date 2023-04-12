# Impact of Instance Choice, Placement, and Communication of Microservice Architecture on Cloud Performance

![](https://github.com/cl456852/eureka/blob/master/gateway/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-04-11%20185202.png)
![](https://github.com/cl456852/eureka/blob/master/gateway/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202023-04-11%20185319.png)
Eureka: a service registry and discovery tool that allows microservices to locate and communicate with each other.  
School Service: a microservice that provides school information based on the requested school name.   
Student Service: a microservice that provides student information based on the requested school name.  
Application Gateway: a gateway service that uses API to call School and Student Service, combine the data, and return it to the client.  
Jmeter: performance test tool.

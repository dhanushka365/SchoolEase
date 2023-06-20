![School Management System](https://github.com/dhanushka365/SchoolEase/assets/66137046/b1509d87-afd1-463d-a15e-3c748ebed843)

##download presentation
[School Management System (3).pdf](https://github.com/dhanushka365/SchoolEase/files/11475123/School.Management.System.3.pdf)

# Introduction
1. [x] The effective management of schools and educational institutions is critical for ensuring student success and improving academic outcomes.
2. [x] To achieve this, a school management system can provide a range of features to support administrative tasks, enhance teaching and learning processes, and promote communication between teachers, students, and parents.
3. [x] Therefore we have designed and implemented a school management system through microservices architecture, which allows for the creation of smaller, independent services that can communicate with each other to provide scalable and efficient cohesive system.

# Architecture

# Micro-services
* ##### The implementation methods used (Netflix software stack)

# Core services
|service                       | Description                                                                            | 
| ---------------------------- | -------------------------------------------------------------------------------------- | 
| Student Microservice         | Student CREATE DELETE UPDATE INSERT                                                    | 
| Teacher Microservice         | Teacher CREATE DELETE UPDATE INSERT                                                    | 
| Course Microservice          | Course CREATE DELETE UPDATE INSERT                                                     | 
| Notification MicroService    | Notification CREATE DELETE                                                             | 

# Utility services
|service                       | Description                                                                                                                                                                 | 
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | 
| Gateway Microservice         | A gateway microservice acts as an entry point for client requests, routing them to appropriate services within a system.                                                    | 
| Zipkin Microservice          | Zipkin is a distributed tracing system used to monitor and troubleshoot microservices-based architectures by tracing requests as they flow through multiple services.       | 
| RabitMQ Microservice         | RabbitMQ is a message broker that enables asynchronous communication between microservices, allowing them to send and receive messages reliably and efficiently.            | 
| Service Discovery            | Service discovery is a mechanism that allows microservices to locate and communicate with each other dynamically without hard-coding their network locations,enabling scalability and flexibility in distributed systems.           |
                                                                                                                | 

# Discovery Server![ServiceDiscovery](https://github.com/dhanushka365/SchoolEase/assets/66137046/457d85b7-5002-4d0c-a090-38b26b219eb7)


# API Gateway

![cloud gateway](https://github.com/dhanushka365/SchoolEase/assets/66137046/9b1f9a1e-8860-45e2-a342-d15ce525b50a)

# User Interface
1. [x] Studen Microservice URIs
* #### Student Login
![student login](https://github.com/dhanushka365/SchoolEase/assets/66137046/6bffb2c0-8c19-4734-b166-55b0287c6ed2)
* #### Student Registration
![student registration](https://github.com/dhanushka365/SchoolEase/assets/66137046/22c13d7b-56c1-473d-acc3-b979e2158446)

# Deployment
- Docker Destop  and Docker hub was used in the project
<img width="367" alt="docker-hub" src="https://github.com/dhanushka365/SchoolEase/assets/66137046/df541d51-d1d3-4050-9353-7aa59794ddc9">

# References
## https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/

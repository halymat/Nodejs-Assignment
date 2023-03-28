## 1. Define Monolithic architecture
 In monolithic architecture, different functional components of the server-side application, such as payment processing, account management, push notifications, and other components, all blend together in a single unit..To make a change to this sort of application requires updating the entire stack by accessing the code base and building and deploying an updated version of the service-side interface
 
 ## 2. Explain microservices in your own understanding
 It is an architectural development style in which the application is made up of smaller services that handle a small portion of the functionality and data by communicating with each other directly using lightweight protocols like HTTP.
 The Microservice architecture has a significant impact on the relationship between the application and the database. Instead of sharing a single database with other microservices, each microservice has its own database. It often results in duplication of some data, but having a database per microservice is essential if you want to benefit from this architecture, as it ensures loose coupling
 
 ## 3. Which of the backend architecture appeals to you and why?
 Microservices appeals to me because of some many reasons.
 It is easy to manage as it is relatively smaller.
If there’s any update in one of the microservices, then we need to redeploy only that microservice.
Microservices are self-contained and, hence, deployed independently. Their start-up and deployment times are relatively less.
It is very easy for a new developer to onboard the project as he needs to understand only a particular microservice providing the functionality he will be working on and not the whole system.
If a particular microservice is facing a large load because of the users using that functionality in excess, then we need to scale out that microservice only. Hence, the microservices architecture supports horizontal scaling.
Each microservice can use different technology based on the business requirements.

## 4. Is Nodejs a multithreaded language?
Nodejs is multithreaded its runs JavaScript code in a single thread, which means that your code can only do one task at a time. However, Node.js itself is multithreaded and provides hidden threads through the libuv library, which handles I/O operations like reading files from a disk or network requests

## 5. What does REPL stand for?
REPL is Read, Evaluate, Print, Loop

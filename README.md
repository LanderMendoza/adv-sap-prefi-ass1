## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- Service Oriented Architecture is a software development model which reuses a various functions or services to combined in different systems in order to build a software application. Each services have their own assigned business task that can be accessed independently. These services can communicate with one another in order to complete the process of software development. SOA's goal is to make it easier to create modular, flexible, and scalable software systems that can adapt to changing business needs.

2. List and discuss the characteristics of SOA.
• Standardized Service Contracts
- It is a detailed description of services that specifies the terms and conditions of a service associated with the both parties involved. It specifies what services will be provided, how they will be delivered, and what both parties should expect. 

• Loose Coupling 
- It refers to a service in which components are independent and interact with minimal dependencies. This allows the flexibility to change one component without significantly affecting others.

• Abstraction
- It refers to a service that allows the logic it encapsulates to be hidden. It keeps things simple, avoids sharing too much information, and allows services to work together easily.

• Service and Reusability
- It is breaking down tasks into separate services that allows to be easily reused in different situations. It saves time and resources by using the same logic in various application instead of creating new one each time.

•Autonomy
- It refers to the independence of each service which allows them to have control over their actions. This independence allows services to operate autonomously and execute their functions without relying on other services.

• Statelessness 
- It means that services should be stateless which each service operates independently without storing information about the current state of other services. It improves scalability and makes it easier to reuse services within a system.

• Discoverability
- It refers to the ability of services to be easily found through a service registry. This allows other components to discover and interact with the accessible services that ensures efficient system navigation and promotes seamless integration.

• Composability
- It refers to the ability of services to break down complex problems into smaller and reusable components helping the system to adapt to different needs. It allows services to exchange various types of information for similar tasks.


• Interoperability
- It refers to the services using common standards that allowing various users to easily access and use the service. This ensures effective collaboration, communication, and compatibility across different systems.

3. Define Microservices.
- Microservice is a software development model in which the application is built as a collection of services. It lets an application to be divided into smaller independent components, each with their own assigned task. Each microservice solves business challenges by interacting with other services through simple interfaces. Microservices improve the scalability and maintainability of complex applications by allowing each independent service to be built, deployed, and updated separately.

4. List and discuss the benefits of using Microservices.
• Independently Deployable
- Independently deployable is one of the benefits of Microservices because it allows the organization to implement changes quickly which reduces time and effort that needed for deployment. Microservice are smaller that allows the services to deployed on their own which lets the organization to work efficiently.

• Right Tool for the Job
- Microservices is right tool for the job because the services can be deployed independently which allows the organization to select the most appropriate tools for each of their task. Microservices make it much easier and less expensive to update individual services, making it simple to keep up with the best technology for the application.

• Precise Scaling
- Precise scaling is one of the advantages of Microservices because it allows you to easily scale only the part of the application that need the specific component which ensures the efficiency and customization to meet your specific needs. 

5. List and discuss the similarities and differences of SOA and Microservices.
Similarities
• Breaking Down Large Applications
- Both SOA and Microservices breaking down large and complex application into smaller services. They both make it easier to add new components or modify existing components without affecting the entire software.

• Enhanced Scalability
- Both SOA and Microservices enhanced scalability because they both allow the organization to develop application faster. They both can adapt to changing in what the organization needs.

• Independent Deployment
- Both SOA and Microservices allows to deployed their services independently. This gives the organization to update and manage each component separately. It also makes it easier to make changes without affecting the entire application.

Differences
• Scope
- SOA are designed to a single service which handles multiple business functions. It allows to reuses a various function in different systems in order to build application. On the other hand, Microservices are designed into a small and independently services. Each microservice has their own function that helps the organization to build an application.

• Communication
- In SOA, each service relies on a shared communication mechanism called an enterprise service bus (ESB). While in Microservices, each service is developed independently with its own communication protocol.

• Data Storage
- In SOA, there is a single data storage layer shared by connected services, facilitating easy access and reuse of data. On the other hand, each Microservice has its own data storage, promoting data independence.



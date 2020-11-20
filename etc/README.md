---
sort: 1
---

# Glossary

### Global Acceleration Service
The Global Acceleration Service provided by G-Express optimizes the transmission section using the dedicated network of a cloud operator, and accelerates Internet application services by minimizing packet loss, jitter, packet delay, and congestion. This greatly enhances the user experience of global application services.

### Accelerator(Global Accelerator)
It is a software system that provides Global Acceleration Services between specific regions to improve the quality of customers' Internet applications. Solbox's Accelerator solution allows service providers to open and manage their services directly through a web portal, and to quickly expand without configuring a separate physical system.<br>
 Global Accelerator consists of two key components - Listener and Endpoint.  

### Listener
The Listener is a software module that composes the Accelerator. It directly receives the data requested by the user to the origin server and accelerates the transmission of user data to the Endpoint in the region where the Backend Server is located. Customers need to create Endpoint where end users are located, which needs global application acceleration service.

### Endpoint
The Endpoint is a software module that composes an Accelerator. It accelerates transmission of user request data received from the Listener to the Backend Server. Customers need to create Endpoint where Backend Server is located, which needs global application acceleration service.

### Backend Server(Origin Server)
It refers to a customer's server that provides Internet application services to end users. 

### Client
It refers to an Internet application service provider that uses the Global Acceleration Service provided by G-Express.

### Region
Refers to the area where Global Acceleration Services can be created. The Global Acceleration Service provided by G-Express is configured using various cloud service platforms and dedicated networks. It refers to a physical location where Listeners and Endpoints, components of Accelerators that provides Global Acceleration Services, can be created.

### Listener Region
It is the physical location where Listener, a component of Accelerator that provides Global Acceleration Service, can be created.  

### Endpoint Region
It is the physical location where Endpoint, a component of Accelerator that provides Global Acceleration Service, can be created.

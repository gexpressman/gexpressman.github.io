# What is G-Express Service?

G-Express Service is a Global Acceleration Service that provides high-quality acceleration services based on a dedicated network to global users of the customer's Internet application service. This can minimize packet loss and service transmission delay of Internet application services and significantly improves user experience.

[![G-Express Service Concept](https://gexpressman.github.io/images/Intro_gex_concept.png)](https://gexpress.solbox.com)<br>
[G-Express Service Pages](https://gexpress.solbox.com)

## System Configuration
Customers need to create a Global Accelerator to use the Global Acceleration Service. The Global Accelerator consists of a Listener and an Endpoint, and the data requested by the customer's Internet application service user is accelerated and transmitted through the Global Accelerator.  

### Listener
The Listener is a software module that composes the Accelerator. It directly receives the data requested by the user to the origin server and accelerates the transmission of user data to the Endpoint in the region where the Backend Server is located. Customers need to create Endpoint where end users are located, which needs global application acceleration service. 

### Endpoint
The Endpoint is a software module that composes an Accelerator. It accelerates transmission of user request data received from the Listener to the Backend Server. Customers need to create Endpoint where Backend Server is located, which needs global application acceleration service.

## Application
### Global Game Acceleration Service
When a global game service user accesses a remote game server, the service quality may vary depending on the location of the user's accesses. The difference in service quality among game users can create an unfair service environment. The Global Acceleration Service provided by G-Express is an acceleration service through a dedicated network between the global service user access area and the game server, ensuring equal service quality among countless global game users. 

![Global Game Service](https://gexpressman.github.io/images/Intro_usage_gameservice.png)

### Smart Office Acceleration Service
When on-promise offices operated by global companies are changed to cloud-based smart offices, global regional offices still frequently experience poor quality of service due to access to smart office services through a dedicated network with the headquarters. In this case, the quality of smart office services in global regional offices can be significantly improved by adopting Global Acceleration Services between global regional offices and smart office service regions. 

![Smart Office Service](https://gexpressman.github.io/images/Intro_usage_smartoffice.png)


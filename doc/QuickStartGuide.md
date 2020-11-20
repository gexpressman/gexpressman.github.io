---
sort: 1
---

# Quick Start Guide

![Quick Start Guide](/images/QuickStart_guide.png)

How to launch the target service for better quality of Internet application services using the Global Acceleration Service is as follows.


> 1. Create a name of the Accelerator and set the data limit allowed for the service.
> 2. Set the Accelerator's Listener in the destination service area to which the end user connects. 
> 3. Set the Endpoint in an area where Backend Server provides Internet application services is located.
> 4. Enter the information about Backend Server(that is, origin server) that provides Internet application services.    

A service opening wizard is provided to create an Accelerator that provides the Global Acceleration Service. How to set it up is described is as follows.

---
## Start Accelerator Setup Wizard

* Click 'Create Accelerator' in the Global Accelerator menu to run the Accelerator Setup Wizard.

![Start Accelerator Setup](/images/QuickStart_Wizard_exec.png)

## Accelerator Settings.

* Create the Accelerator name and set the data limit allowed for the service.

> a. Create the name of the Accelerator.<br>
> b. Set the monthly data limit for the service using Global Acceleration Service. Customers cannot use service beyond the data usage limit. If necessary, it is possible to adjust the data usage.<br>
> c. Click the 'Next' button.<br>


![Accelerator Setting Screenshot](/images/QuickStart_Wizard_Accelerator.png)
  
## Listener Configuration.

* Set the Accelerator's Listener in the destination service area to which end users are connected. ([See Listener setting.](/doc/Listener.html#listener-modify))

> a. Create the name of the Listener.<br>
> b. Select the Listener region, which is the physical location where the Listener will be created.<br>
> c. Set the protocol used in the Internet application service of the customer to provide the acceleration service. The Global Acceleration Service currently supports TCP and UDP protocols.<br>
> d. Set the service port to be used in the customer's Internet application service. Example) HTTP web service port: 80<br>
> e. Click the 'Next' button.<br> 

![Listener Setting Screenshot](/images/QuickStart_Wizard_Listener.png)

## Endpoint and Backend Server Settings

* Set the Endpoint and backend server(that is, the origin server) information in the region where the backend server providing Internet application service is located. ([Endpoint Configuration](/doc/Endpoint.html#endpoint-Edit) and [Refer to Backend Server Configuration.](/doc/Endpoint.html#backend-server-Edit))

> a. Create the name of the Endpoint.<br>
> b. Select the Endpoint region, which is the physical location where the Endpoint will be created.<br>
>
> c. Enter the IP address information of the Backend Server(that is, the origin server), which provides the customer's Internet application service.<br>
> d. Enter the service port information of the Backend Server(that is, the origin server), which provides the customer's Internet application service. Example) HTTP web service port: 80<br>
> e. Click the 'Creater Accelerator' button to complete the Accelerator creation.<br>

![Endpoint and Backend Server Setting Screenshot](/images/QuickStart_Wizard_Endpoint.png)

## Register customer's Accelerator IP

* Set the customer's DNS and others to allow the end user to access the Accelerator's static IP address when accessing the Internet application service. Depending on how the customer provides Internet application services, additional settings are required to allow the user's request to be sent to the accelerator.

![Accelerator IP Confirmation Screenshot](/images/QuickStart_Wizard_Last.png)



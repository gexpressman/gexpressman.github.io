---
sort: 4
---

# Endpoint

## Endpoint Details View

![Endpoint Details View Screenshot](/images/Endpoint_Details.png)

**Endpoint**

| Items | Description |
|---|---|
| Endpoint Name | This is the Endpoint name that has been created.  |
| Endpoint SEQ | This is a unique number that can identify the Endpoint.  |
| Endpoint Region | This is the information about the physical location where the Endpoint was created.  |
| Created | The date the Endpoint was created.  |
| Edited | Last modified date.  |

**Backend Server List**

| Items | Description |
|---|---|
| IP | The IP address information of the Backend Server(that is, the origin server), which provides the customer's Internet application service.  |
| Port | The port information of the Backend Server(that is, the origin server), which provides the customer's Internet application service.  |

## Edit Endpoint

![Edit Endpoint Screenshot](/images/Endpoint_Edit.png)

| Setting items | Description |
|---|---|
| Endpoint Name | Edit the name of the Endpoint.<br> Please enter a combination of upper/lower case and numbers without spaces in the middle. You can enter a minimum of 4 characters to a maximum of 50 characters.  |
| Endpoint Region  | The Endpoint Region is not editable. |

## Edit Backend Server

![Edit Endpoint Screenshot](/images/Backend_Edit.png)

| Setting items | Description |
|---  |---|
| Add | If you click the ![Icon Add button](/images/Icon_Add.png) button on the right side of Backend Server Configration, you can add an EndBackend Server.   |
| IP | Enter the IP address of the Backend Server (that is, the origin server), which is the target server for the Global Acceleration Service.  |
| Port | Modify the Backend Server port.<br> Use a comma(,) to specify multiple service ports, or dash(-) to specify the service port as a range. <br>The valid service port range is 1~65535.  You can enter up to 1000 ports. *(However, for TCP, 1001, 1002 and 8181 ports cannot be used.)*<br> Example) 8080, 80, 90 or 9000-10000<br> *Note) The service ports cannot be set to duplicate Example) 90, 80, 90: This cannot set because 90 is a duplicate port.*  |
| Actions | Delete the registered Backend Server.  |






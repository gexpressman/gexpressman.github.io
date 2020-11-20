---
sort: 3
---

# Listener

## Listener Details View

![Listener Details View](/images/Listener_Details.png)

**Listener**

| Items | Description |
|---|---|
| Listener Name | This is the name of the Listener that has been created.  |
| Listener SEQ | This is a unique number that can identify each Listener.  |
| Listener Region | This is the information about the physical location where the Listener was created.  |
| IP Address | The IP assigned to the Listener.  |
| Port | This is the protocol information used in the Internet application service of the customer to provide the Acceleration service.  |
| Protocol | This is the port information used in the customer's Internet application service to provide the Acceleration service.  |
| Created | The date the listener was created.  |
| Edited | Last modified date.   |

**Endpoint List**

| Items | Description |
|---|---|
| Endpoint Name | This is the Endpoint name that has been created.  |
| Endpoint SEQ | This is a unique number to identify each Endpoint.  |
| Endpoint Region | This is the information about the physical location where the Endpoint was created. |

## Edit Listener

![Edit Listener Screenshot](/images/Listener_Edit.png)

| Setting items | Description |
|--- |---|
| Listener Name | You can change the name of the Listener.<br> Please enter a combination of upper/lower case and numbers without spaces in the middle. You can enter a minimum of 4 characters to a maximum of 50 characters.    |
| Listener Region | The Listener Region is not editable.   |
| Listener Protocol | Modify the protocol that will receive the data requested by the user.<br> Currently, UDP and TCP are supported.  |
| Listener Ports | Modify the service port to receive the data requested by the user.<br> Use a comma(,) to specify multiple service ports  or dash(-) to specify service ports as a range.<br> The valid service port range is 1~65535.  You can enter up to 1000 ports. However, for TCP, 1001, 1002 and 8181 ports cannot be used.<br> Example) 8080, 80, 90 or 9000-10000<br> *Note) The service ports cannot be set to duplicate. Example) 90, 80, 90: This cannot set because 90 is a duplicate port.* |



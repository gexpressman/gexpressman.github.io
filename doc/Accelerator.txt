---
sort: 2
---

# Accelerator

## Accelerator list

![Accelerator List](/images/Accelerator_List.png)

### Search

Search by the Accelerator name, IP or Region.

**Items**

| Items | Description |
|---|---|
| Name | This is the Accelerator name that has been created.  |
| Static IP Address | The IP assigned to the Listener.  |
| Listener Region | Information about Listener Region  |
| Endpoint Region | Information about Endpoint Region  |
| Enabled | It shows the the service in use.<br> Even if the service status shows Off, service billing continuously occurs because the Accelerator is still in use.<br>   |
| Status | It shows the deployment status.<br> -**In Progress:** The service setup is in progress. <Br> - **Deployed:** The service setting is complete |
| Edited | First created or last modified date.  |

### Accelerator Details View

![Accelerator Details View](/images/Accelerator_List_Details.png)

**Accelerator Configuration**

|Items | Description |
|---|---|
| Accelerator Name | This is the Accelerator name that has been created.  |
| Accelerator SEQ | This is a unique number that can identify each Accelerator.  |
| Bandwidth Cap.  | Information on the maximum usage that can be used in one month using the Acceleration Service.  |
| Enabled | It shows the the service in use.<br> Even if the service status shows Off, service billing continuously occurs because the Accelerator is still in use.<br>   |
| Provisioning Status | It shows the deployment status.<br> -**In Progress:** The service setup is in progress. <Br> - **Deployed:** The service setting is complete   |
| Created | The date the acceleration service was created.  |
| Edited | Last modified date.  |

**Listener List**

|Items | Description |
|---|---|
| Listener Name | This is the Listener name that has been created.  |
| Listener SEQ | This is a unique number that can identify each Listener.  |
| Listener Region | This is the information about the physical location where the Listener was created.  |
| IP Address | IP assigned to the Listener.  |
| Port and Protocol | This is the protocol and port information used in the customer's Internet application service to provide the Acceleration service.   |
| Endpoint Region | This is the information about the physical location where the Endpoint was created.  |
| Status | This is the status of the Listener in the acceleration service |

## Edit Accelerator

![Eit Accelerator](/images/Accelerator_List_Edit.png)

| Setting Items | Description |
|---|---|
| Accelerator Name | Modify the name of the Accelerator.<br> Please enter the Global Accelerator's name . The name should be easy to distinguish from other Global Accelerators and is easy to remember.<br> It must be entered in combination of upper/lower case and numbers without spaces. You can enter a minimum of 4 characters to a maximum of 50 characters.   |
| Bandwidth Cap.  | Set the monthly data usage limit for the service using the Global Acceleration Service.<br> The service volume cannot exceed the monthly data usage limit. If necessary, the monthly usage limit can be adjusted.<br> The usage range is from a minimum of 2Gbps to a maximum of 10Gbps.  |
| Enabled | Enable or disable the Global Acceleration Service. To remove the acceleration service, the service should be disabled first.<br> Even if the acceleration service is Off, service billing continuously occurs until the Accelerator is removed.  |

## Delete Accelerator

![Edit Accelerator](/images/Accelerator_List_Delete.png)

- Remove the acceleration service that has been created.
- Please keep in mind that the service can be removed only after the acceleration service is deactivated.




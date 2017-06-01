# ProcessmakerApi

All URIs are relative to *https://CHANGEME.api.processmaker.io/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addClient**](ProcessmakerApi.md#addClient) | **POST** /users/{user_id}/clients | 
[**addEvent**](ProcessmakerApi.md#addEvent) | **POST** /processes/{process_id}/events | 
[**addEventConnector**](ProcessmakerApi.md#addEventConnector) | **POST** /processes/{process_id}/events/{event_id}/connectors | 
[**addFlow**](ProcessmakerApi.md#addFlow) | **POST** /processes/{process_id}/flows | 
[**addGateway**](ProcessmakerApi.md#addGateway) | **POST** /processes/{process_id}/gateways | 
[**addGroup**](ProcessmakerApi.md#addGroup) | **POST** /groups | 
[**addGroupsToTask**](ProcessmakerApi.md#addGroupsToTask) | **PUT** /processes/{process_id}/tasks/{task_id}/groups | 
[**addInputOutput**](ProcessmakerApi.md#addInputOutput) | **POST** /processes/{process_id}/tasks/{task_id}/inputoutput | 
[**addInstance**](ProcessmakerApi.md#addInstance) | **POST** /processes/{process_id}/instances | 
[**addProcess**](ProcessmakerApi.md#addProcess) | **POST** /processes | 
[**addTask**](ProcessmakerApi.md#addTask) | **POST** /processes/{process_id}/tasks | 
[**addTaskConnector**](ProcessmakerApi.md#addTaskConnector) | **POST** /processes/{process_id}/tasks/{task_id}/connectors | 
[**addUser**](ProcessmakerApi.md#addUser) | **POST** /users | 
[**addUsersToGroup**](ProcessmakerApi.md#addUsersToGroup) | **PUT** /groups/{id}/users | 
[**deleteClient**](ProcessmakerApi.md#deleteClient) | **DELETE** /users/{user_id}/clients/{client_id} | 
[**deleteEvent**](ProcessmakerApi.md#deleteEvent) | **DELETE** /processes/{process_id}/events/{event_id} | 
[**deleteEventConnector**](ProcessmakerApi.md#deleteEventConnector) | **DELETE** /processes/{process_id}/events/{event_id}/connectors/{connector_id} | 
[**deleteFlow**](ProcessmakerApi.md#deleteFlow) | **DELETE** /processes/{process_id}/flows/{flow_id} | 
[**deleteGateway**](ProcessmakerApi.md#deleteGateway) | **DELETE** /processes/{process_id}/gateways/{gateway_id} | 
[**deleteGroup**](ProcessmakerApi.md#deleteGroup) | **DELETE** /groups/{id} | 
[**deleteInputOutput**](ProcessmakerApi.md#deleteInputOutput) | **DELETE** /processes/{process_id}/tasks/{task_id}/inputoutput/{inputoutput_uid} | 
[**deleteInstance**](ProcessmakerApi.md#deleteInstance) | **DELETE** /processes/{process_id}/instances/{instance_id} | 
[**deleteProcess**](ProcessmakerApi.md#deleteProcess) | **DELETE** /processes/{id} | 
[**deleteTask**](ProcessmakerApi.md#deleteTask) | **DELETE** /processes/{process_id}/tasks/{task_id} | 
[**deleteTaskConnector**](ProcessmakerApi.md#deleteTaskConnector) | **DELETE** /processes/{process_id}/tasks/{task_id}/connectors/{connector_id} | 
[**deleteUser**](ProcessmakerApi.md#deleteUser) | **DELETE** /users/{id} | 
[**eventTrigger**](ProcessmakerApi.md#eventTrigger) | **POST** /processes/{process_id}/events/{event_id}/trigger | 
[**findClientById**](ProcessmakerApi.md#findClientById) | **GET** /users/{user_id}/clients/{client_id} | 
[**findClients**](ProcessmakerApi.md#findClients) | **GET** /users/{user_id}/clients | 
[**findDataModel**](ProcessmakerApi.md#findDataModel) | **GET** /processes/{process_id}/instances/{instance_id}/datamodel | 
[**findEventById**](ProcessmakerApi.md#findEventById) | **GET** /processes/{process_id}/events/{event_id} | 
[**findEventConnectorById**](ProcessmakerApi.md#findEventConnectorById) | **GET** /processes/{process_id}/events/{event_id}/connectors/{connector_id} | 
[**findEventConnectors**](ProcessmakerApi.md#findEventConnectors) | **GET** /processes/{process_id}/events/{event_id}/connectors | 
[**findEvents**](ProcessmakerApi.md#findEvents) | **GET** /processes/{process_id}/events | 
[**findFlowById**](ProcessmakerApi.md#findFlowById) | **GET** /processes/{process_id}/flows/{flow_id} | 
[**findFlows**](ProcessmakerApi.md#findFlows) | **GET** /processes/{process_id}/flows | 
[**findGatewayById**](ProcessmakerApi.md#findGatewayById) | **GET** /processes/{process_id}/gateways/{gateway_id} | 
[**findGateways**](ProcessmakerApi.md#findGateways) | **GET** /processes/{process_id}/gateways | 
[**findGroupById**](ProcessmakerApi.md#findGroupById) | **GET** /groups/{id} | 
[**findGroups**](ProcessmakerApi.md#findGroups) | **GET** /groups | 
[**findInputOutputById**](ProcessmakerApi.md#findInputOutputById) | **GET** /processes/{process_id}/tasks/{task_id}/inputoutput/{inputoutput_uid} | 
[**findInputOutputs**](ProcessmakerApi.md#findInputOutputs) | **GET** /processes/{process_id}/tasks/{task_id}/inputoutput | 
[**findInstanceById**](ProcessmakerApi.md#findInstanceById) | **GET** /processes/{process_id}/instances/{instance_id} | 
[**findInstances**](ProcessmakerApi.md#findInstances) | **GET** /processes/{process_id}/instances | 
[**findProcessById**](ProcessmakerApi.md#findProcessById) | **GET** /processes/{id} | 
[**findProcesses**](ProcessmakerApi.md#findProcesses) | **GET** /processes | 
[**findTaskById**](ProcessmakerApi.md#findTaskById) | **GET** /processes/{process_id}/tasks/{task_id} | 
[**findTaskConnectorById**](ProcessmakerApi.md#findTaskConnectorById) | **GET** /processes/{process_id}/tasks/{task_id}/connectors/{connector_id} | 
[**findTaskConnectors**](ProcessmakerApi.md#findTaskConnectors) | **GET** /processes/{process_id}/tasks/{task_id}/connectors | 
[**findTaskInstanceById**](ProcessmakerApi.md#findTaskInstanceById) | **GET** /task_instances/{task_instance_id} | 
[**findTaskInstances**](ProcessmakerApi.md#findTaskInstances) | **GET** /task_instances | 
[**findTasks**](ProcessmakerApi.md#findTasks) | **GET** /processes/{process_id}/tasks | 
[**findUserById**](ProcessmakerApi.md#findUserById) | **GET** /users/{id} | 
[**findUsers**](ProcessmakerApi.md#findUsers) | **GET** /users | 
[**importBpmnFile**](ProcessmakerApi.md#importBpmnFile) | **POST** /processes/import | 
[**myselfUser**](ProcessmakerApi.md#myselfUser) | **GET** /users/myself | 
[**removeGroupsFromTask**](ProcessmakerApi.md#removeGroupsFromTask) | **DELETE** /processes/{process_id}/tasks/{task_id}/groups | 
[**removeUsersFromGroup**](ProcessmakerApi.md#removeUsersFromGroup) | **DELETE** /groups/{id}/users | 
[**syncGroupsToTask**](ProcessmakerApi.md#syncGroupsToTask) | **POST** /processes/{process_id}/tasks/{task_id}/groups | 
[**syncUsersToGroup**](ProcessmakerApi.md#syncUsersToGroup) | **POST** /groups/{id}/users | 
[**updateClient**](ProcessmakerApi.md#updateClient) | **PUT** /users/{user_id}/clients/{client_id} | 
[**updateEvent**](ProcessmakerApi.md#updateEvent) | **PUT** /processes/{process_id}/events/{event_id} | 
[**updateEventConnector**](ProcessmakerApi.md#updateEventConnector) | **PUT** /processes/{process_id}/events/{event_id}/connectors/{connector_id} | 
[**updateFlow**](ProcessmakerApi.md#updateFlow) | **PUT** /processes/{process_id}/flows/{flow_id} | 
[**updateGateway**](ProcessmakerApi.md#updateGateway) | **PUT** /processes/{process_id}/gateways/{gateway_id} | 
[**updateGroup**](ProcessmakerApi.md#updateGroup) | **PUT** /groups/{id} | 
[**updateInputOutput**](ProcessmakerApi.md#updateInputOutput) | **PUT** /processes/{process_id}/tasks/{task_id}/inputoutput/{inputoutput_uid} | 
[**updateInstance**](ProcessmakerApi.md#updateInstance) | **PUT** /processes/{process_id}/instances/{instance_id} | 
[**updateProcess**](ProcessmakerApi.md#updateProcess) | **PUT** /processes/{id} | 
[**updateTask**](ProcessmakerApi.md#updateTask) | **PUT** /processes/{process_id}/tasks/{task_id} | 
[**updateTaskConnector**](ProcessmakerApi.md#updateTaskConnector) | **PUT** /processes/{process_id}/tasks/{task_id}/connectors/{connector_id} | 
[**updateTaskInstance**](ProcessmakerApi.md#updateTaskInstance) | **PATCH** /task_instances/{task_instance_id} | 
[**updateUser**](ProcessmakerApi.md#updateUser) | **PUT** /users/{id} | 


<a name="addClient"></a>
# **addClient**
> ClientItem addClient(userId, clientCreateItem)



This method creates a new Oauth client for the user

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String userId = "userId_example"; // String | ID of the user related to the Oauth client
ClientCreateItem clientCreateItem = new ClientCreateItem(); // ClientCreateItem | JSON API with the Oauth Client object to add
try {
    ClientItem result = apiInstance.addClient(userId, clientCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addClient");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **String**| ID of the user related to the Oauth client |
 **clientCreateItem** | [**ClientCreateItem**](ClientCreateItem.md)| JSON API with the Oauth Client object to add |

### Return type

[**ClientItem**](ClientItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addEvent"></a>
# **addEvent**
> EventItem addEvent(processId, eventCreateItem)



This method creates the new event.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of the process related to the event
EventCreateItem eventCreateItem = new EventCreateItem(); // EventCreateItem | JSON API response with the Event object to add
try {
    EventItem result = apiInstance.addEvent(processId, eventCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addEvent");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of the process related to the event |
 **eventCreateItem** | [**EventCreateItem**](EventCreateItem.md)| JSON API response with the Event object to add |

### Return type

[**EventItem**](EventItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addEventConnector"></a>
# **addEventConnector**
> EventConnector1 addEventConnector(processId, eventId, eventConnectorCreateItem)



This method is intended for creating a new Event connector.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to fetch
String eventId = "eventId_example"; // String | ID of Event to fetch
EventConnectorCreateItem eventConnectorCreateItem = new EventConnectorCreateItem(); // EventConnectorCreateItem | JSON API with the EventConnector object to add
try {
    EventConnector1 result = apiInstance.addEventConnector(processId, eventId, eventConnectorCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addEventConnector");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to fetch |
 **eventId** | **String**| ID of Event to fetch |
 **eventConnectorCreateItem** | [**EventConnectorCreateItem**](EventConnectorCreateItem.md)| JSON API with the EventConnector object to add |

### Return type

[**EventConnector1**](EventConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addFlow"></a>
# **addFlow**
> FlowItem addFlow(processId, flowCreateItem)



This method creates a new Sequence flow

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of the process related to the flow
FlowCreateItem flowCreateItem = new FlowCreateItem(); // FlowCreateItem | JSON API response with the Flow object to add
try {
    FlowItem result = apiInstance.addFlow(processId, flowCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addFlow");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of the process related to the flow |
 **flowCreateItem** | [**FlowCreateItem**](FlowCreateItem.md)| JSON API response with the Flow object to add |

### Return type

[**FlowItem**](FlowItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addGateway"></a>
# **addGateway**
> GatewayItem addGateway(processId, gatewayCreateItem)



This method creates a new gateway.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of the process related to the gateway
GatewayCreateItem gatewayCreateItem = new GatewayCreateItem(); // GatewayCreateItem | JSON API response with the gateway object to add
try {
    GatewayItem result = apiInstance.addGateway(processId, gatewayCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addGateway");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of the process related to the gateway |
 **gatewayCreateItem** | [**GatewayCreateItem**](GatewayCreateItem.md)| JSON API response with the gateway object to add |

### Return type

[**GatewayItem**](GatewayItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addGroup"></a>
# **addGroup**
> GroupItem addGroup(groupCreateItem)



This method creates a new group.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
GroupCreateItem groupCreateItem = new GroupCreateItem(); // GroupCreateItem | JSON API with the Group object to add
try {
    GroupItem result = apiInstance.addGroup(groupCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addGroup");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **groupCreateItem** | [**GroupCreateItem**](GroupCreateItem.md)| JSON API with the Group object to add |

### Return type

[**GroupItem**](GroupItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addGroupsToTask"></a>
# **addGroupsToTask**
> ResultSuccess addGroupsToTask(processId, taskId, taskAddGroupsItem)



This method assigns group(s) to the choosen task

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID
String taskId = "taskId_example"; // String | ID of task to be modified
TaskAddGroupsItem taskAddGroupsItem = new TaskAddGroupsItem(); // TaskAddGroupsItem | JSON API with Groups ID's to add
try {
    ResultSuccess result = apiInstance.addGroupsToTask(processId, taskId, taskAddGroupsItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addGroupsToTask");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID |
 **taskId** | **String**| ID of task to be modified |
 **taskAddGroupsItem** | [**TaskAddGroupsItem**](TaskAddGroupsItem.md)| JSON API with Groups ID&#39;s to add |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addInputOutput"></a>
# **addInputOutput**
> InputOutputItem addInputOutput(processId, taskId, inputOutputCreateItem)



This method creates a new Input/Output object

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID related to Input/Output object
String taskId = "taskId_example"; // String | Task instance ID related to Input/Output object
InputOutputCreateItem inputOutputCreateItem = new InputOutputCreateItem(); // InputOutputCreateItem | Create and add a new Input/Output object with JSON API
try {
    InputOutputItem result = apiInstance.addInputOutput(processId, taskId, inputOutputCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addInputOutput");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID related to Input/Output object |
 **taskId** | **String**| Task instance ID related to Input/Output object |
 **inputOutputCreateItem** | [**InputOutputCreateItem**](InputOutputCreateItem.md)| Create and add a new Input/Output object with JSON API |

### Return type

[**InputOutputItem**](InputOutputItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addInstance"></a>
# **addInstance**
> InstanceItem addInstance(processId, instanceCreateItem)



This method creates a new instance.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID related to the nstance
InstanceCreateItem instanceCreateItem = new InstanceCreateItem(); // InstanceCreateItem | JSON API response with the Instance object to add
try {
    InstanceItem result = apiInstance.addInstance(processId, instanceCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addInstance");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID related to the nstance |
 **instanceCreateItem** | [**InstanceCreateItem**](InstanceCreateItem.md)| JSON API response with the Instance object to add |

### Return type

[**InstanceItem**](InstanceItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addProcess"></a>
# **addProcess**
> ProcessItem addProcess(processCreateItem)



This method creates a new process

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
ProcessCreateItem processCreateItem = new ProcessCreateItem(); // ProcessCreateItem | JSON API response with the Process object to add
try {
    ProcessItem result = apiInstance.addProcess(processCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addProcess");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processCreateItem** | [**ProcessCreateItem**](ProcessCreateItem.md)| JSON API response with the Process object to add |

### Return type

[**ProcessItem**](ProcessItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addTask"></a>
# **addTask**
> TaskItem addTask(processId, taskCreateItem)



This method creates a new task.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID related to the task
TaskCreateItem taskCreateItem = new TaskCreateItem(); // TaskCreateItem | JSON API with the Task object to add
try {
    TaskItem result = apiInstance.addTask(processId, taskCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addTask");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID related to the task |
 **taskCreateItem** | [**TaskCreateItem**](TaskCreateItem.md)| JSON API with the Task object to add |

### Return type

[**TaskItem**](TaskItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addTaskConnector"></a>
# **addTaskConnector**
> TaskConnector1 addTaskConnector(processId, taskId, taskConnectorCreateItem)



This method is intended for creating a new task connector.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to fetch
String taskId = "taskId_example"; // String | ID of Task to fetch
TaskConnectorCreateItem taskConnectorCreateItem = new TaskConnectorCreateItem(); // TaskConnectorCreateItem | JSON API with the TaskConnector object to add
try {
    TaskConnector1 result = apiInstance.addTaskConnector(processId, taskId, taskConnectorCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addTaskConnector");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to fetch |
 **taskId** | **String**| ID of Task to fetch |
 **taskConnectorCreateItem** | [**TaskConnectorCreateItem**](TaskConnectorCreateItem.md)| JSON API with the TaskConnector object to add |

### Return type

[**TaskConnector1**](TaskConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addUser"></a>
# **addUser**
> UserItem addUser(userCreateItem)



This method creates a new user in the system.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
UserCreateItem userCreateItem = new UserCreateItem(); // UserCreateItem | JSON API with the User object to add
try {
    UserItem result = apiInstance.addUser(userCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addUser");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userCreateItem** | [**UserCreateItem**](UserCreateItem.md)| JSON API with the User object to add |

### Return type

[**UserItem**](UserItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="addUsersToGroup"></a>
# **addUsersToGroup**
> ResultSuccess addUsersToGroup(id, groupAddUsersItem)



This method adds one or more new users to a group.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of group to be modified
GroupAddUsersItem groupAddUsersItem = new GroupAddUsersItem(); // GroupAddUsersItem | JSON API response with array of users ID's
try {
    ResultSuccess result = apiInstance.addUsersToGroup(id, groupAddUsersItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#addUsersToGroup");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of group to be modified |
 **groupAddUsersItem** | [**GroupAddUsersItem**](GroupAddUsersItem.md)| JSON API response with array of users ID&#39;s |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteClient"></a>
# **deleteClient**
> ResultSuccess deleteClient(userId, clientId)



This method deletes an Oauth client using the client and user IDs.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String userId = "userId_example"; // String | User ID
String clientId = "clientId_example"; // String | ID of client to delete
try {
    ResultSuccess result = apiInstance.deleteClient(userId, clientId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteClient");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **String**| User ID |
 **clientId** | **String**| ID of client to delete |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteEvent"></a>
# **deleteEvent**
> ResultSuccess deleteEvent(processId, eventId)



This method deletes an event using the event ID and process ID

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID
String eventId = "eventId_example"; // String | ID of event to delete
try {
    ResultSuccess result = apiInstance.deleteEvent(processId, eventId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteEvent");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID |
 **eventId** | **String**| ID of event to delete |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteEventConnector"></a>
# **deleteEventConnector**
> ResultSuccess deleteEventConnector(processId, eventId, connectorId)



This method is intended for deleting a single Event connector based on Event ID, Process ID and Connector ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of of Process item
String eventId = "eventId_example"; // String | ID of item to fetch
String connectorId = "connectorId_example"; // String | ID of EventConnector to fetch
try {
    ResultSuccess result = apiInstance.deleteEventConnector(processId, eventId, connectorId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteEventConnector");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of of Process item |
 **eventId** | **String**| ID of item to fetch |
 **connectorId** | **String**| ID of EventConnector to fetch |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteFlow"></a>
# **deleteFlow**
> ResultSuccess deleteFlow(processId, flowId)



This method deletes a sequence flow using the flow ID and process ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID
String flowId = "flowId_example"; // String | ID of flow to delete
try {
    ResultSuccess result = apiInstance.deleteFlow(processId, flowId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteFlow");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID |
 **flowId** | **String**| ID of flow to delete |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteGateway"></a>
# **deleteGateway**
> ResultSuccess deleteGateway(processId, gatewayId)



This method is deletes a single item using the gateway ID and process ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID
String gatewayId = "gatewayId_example"; // String | ID of Process to delete
try {
    ResultSuccess result = apiInstance.deleteGateway(processId, gatewayId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteGateway");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID |
 **gatewayId** | **String**| ID of Process to delete |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteGroup"></a>
# **deleteGroup**
> ResultSuccess deleteGroup(id)



This method deletes a group using the group ID

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of group to delete
try {
    ResultSuccess result = apiInstance.deleteGroup(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteGroup");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of group to delete |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteInputOutput"></a>
# **deleteInputOutput**
> ResultSuccess deleteInputOutput(processId, taskId, inputoutputUid)



This method deletes the Input/Output based on the Input/Output ID, process ID and task ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID related to the Input/Output object
String taskId = "taskId_example"; // String | Task instance ID related to Input/Output object
String inputoutputUid = "inputoutputUid_example"; // String | Input/Output ID to fetch
try {
    ResultSuccess result = apiInstance.deleteInputOutput(processId, taskId, inputoutputUid);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteInputOutput");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID related to the Input/Output object |
 **taskId** | **String**| Task instance ID related to Input/Output object |
 **inputoutputUid** | **String**| Input/Output ID to fetch |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteInstance"></a>
# **deleteInstance**
> ResultSuccess deleteInstance(processId, instanceId)



This method deletes an instance using the instance ID and process ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID
String instanceId = "instanceId_example"; // String | ID of instance to delete
try {
    ResultSuccess result = apiInstance.deleteInstance(processId, instanceId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteInstance");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID |
 **instanceId** | **String**| ID of instance to delete |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteProcess"></a>
# **deleteProcess**
> ResultSuccess deleteProcess(id)



This method deletes a process using the process ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | Process ID to delete
try {
    ResultSuccess result = apiInstance.deleteProcess(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteProcess");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| Process ID to delete |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteTask"></a>
# **deleteTask**
> ResultSuccess deleteTask(processId, taskId)



This method deletes a task using the task ID and process ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID
String taskId = "taskId_example"; // String | ID of task to delete
try {
    ResultSuccess result = apiInstance.deleteTask(processId, taskId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteTask");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID |
 **taskId** | **String**| ID of task to delete |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteTaskConnector"></a>
# **deleteTaskConnector**
> ResultSuccess deleteTaskConnector(processId, taskId, connectorId)



This method is intended for deleting a single Task connector based on Task ID, Process ID and Connector ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process item to fetch
String taskId = "taskId_example"; // String | ID of Task item to fetch
String connectorId = "connectorId_example"; // String | ID of TaskConnector to fetch
try {
    ResultSuccess result = apiInstance.deleteTaskConnector(processId, taskId, connectorId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteTaskConnector");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process item to fetch |
 **taskId** | **String**| ID of Task item to fetch |
 **connectorId** | **String**| ID of TaskConnector to fetch |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="deleteUser"></a>
# **deleteUser**
> ResultSuccess deleteUser(id)



This method deletes a user from the system.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of user to delete
try {
    ResultSuccess result = apiInstance.deleteUser(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#deleteUser");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of user to delete |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="eventTrigger"></a>
# **eventTrigger**
> DataModelItem1 eventTrigger(processId, eventId, triggerEventCreateItem)



This method starts/triggers an event.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID related to the event
String eventId = "eventId_example"; // String | ID of event to trigger
TriggerEventCreateItem triggerEventCreateItem = new TriggerEventCreateItem(); // TriggerEventCreateItem | Json with some parameters
try {
    DataModelItem1 result = apiInstance.eventTrigger(processId, eventId, triggerEventCreateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#eventTrigger");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID related to the event |
 **eventId** | **String**| ID of event to trigger |
 **triggerEventCreateItem** | [**TriggerEventCreateItem**](TriggerEventCreateItem.md)| Json with some parameters |

### Return type

[**DataModelItem1**](DataModelItem1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findClientById"></a>
# **findClientById**
> ClientItem findClientById(userId, clientId)



This method is retrieves an Oauth client based on its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String userId = "userId_example"; // String | ID of user to retrieve
String clientId = "clientId_example"; // String | ID of client to retrieve
try {
    ClientItem result = apiInstance.findClientById(userId, clientId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findClientById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **String**| ID of user to retrieve |
 **clientId** | **String**| ID of client to retrieve |

### Return type

[**ClientItem**](ClientItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findClients"></a>
# **findClients**
> ClientCollection findClients(userId, pagefindProcessById, perPage)



This method retrieves all existing clients belonging to an user.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String userId = "userId_example"; // String | User ID related to the clients
Integer pagefindProcessById = 1; // Integer | Page numbers to fetch
Integer perPage = 15; // Integer | Amount of items per page
try {
    ClientCollection result = apiInstance.findClients(userId, pagefindProcessById, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findClients");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **String**| User ID related to the clients |
 **pagefindProcessById** | **Integer**| Page numbers to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per page | [optional] [default to 15]

### Return type

[**ClientCollection**](ClientCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findDataModel"></a>
# **findDataModel**
> DataModelItem1 findDataModel(processId, instanceId, page, perPage)



This method returns the instance DataModel and lets the user work with it directly

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process to return
String instanceId = "instanceId_example"; // String | ID of instance to return
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per Page
try {
    DataModelItem1 result = apiInstance.findDataModel(processId, instanceId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findDataModel");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process to return |
 **instanceId** | **String**| ID of instance to return |
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per Page | [optional] [default to 15]

### Return type

[**DataModelItem1**](DataModelItem1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findEventById"></a>
# **findEventById**
> EventItem findEventById(processId, eventId)



This method retrieves an event using its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process to return
String eventId = "eventId_example"; // String | ID of event to return
try {
    EventItem result = apiInstance.findEventById(processId, eventId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findEventById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process to return |
 **eventId** | **String**| ID of event to return |

### Return type

[**EventItem**](EventItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findEventConnectorById"></a>
# **findEventConnectorById**
> EventConnector1 findEventConnectorById(processId, eventId, connectorId)



This method returns all Event connectors related to the run Process and Event.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to fetch
String eventId = "eventId_example"; // String | ID of Event to fetch
String connectorId = "connectorId_example"; // String | ID of EventConnector to fetch
try {
    EventConnector1 result = apiInstance.findEventConnectorById(processId, eventId, connectorId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findEventConnectorById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to fetch |
 **eventId** | **String**| ID of Event to fetch |
 **connectorId** | **String**| ID of EventConnector to fetch |

### Return type

[**EventConnector1**](EventConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findEventConnectors"></a>
# **findEventConnectors**
> EventConnectorsCollection findEventConnectors(processId, eventId, page, perPage)



This method returns all Event connectors related to the run Process and Event.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to fetch
String eventId = "eventId_example"; // String | ID of Task to fetch
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per Page
try {
    EventConnectorsCollection result = apiInstance.findEventConnectors(processId, eventId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findEventConnectors");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to fetch |
 **eventId** | **String**| ID of Task to fetch |
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per Page | [optional] [default to 15]

### Return type

[**EventConnectorsCollection**](EventConnectorsCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findEvents"></a>
# **findEvents**
> EventCollection findEvents(processId, page, perPage)



This method returns all events related to the runned process

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process related to the event
Integer page = 1; // Integer | Page numbers to fetch
Integer perPage = 15; // Integer | Amount of items per Page
try {
    EventCollection result = apiInstance.findEvents(processId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findEvents");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process related to the event |
 **page** | **Integer**| Page numbers to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per Page | [optional] [default to 15]

### Return type

[**EventCollection**](EventCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findFlowById"></a>
# **findFlowById**
> FlowItem findFlowById(processId, flowId)



This method retrieves a flow based on its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process to return
String flowId = "flowId_example"; // String | ID of flow to return
try {
    FlowItem result = apiInstance.findFlowById(processId, flowId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findFlowById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process to return |
 **flowId** | **String**| ID of flow to return |

### Return type

[**FlowItem**](FlowItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findFlows"></a>
# **findFlows**
> FlowCollection findFlows(processId, page, perPage)



This method retrieves all existing flows.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process related to the flow
Integer page = 1; // Integer | Page numbers to fetch
Integer perPage = 15; // Integer | Amount of items per Page
try {
    FlowCollection result = apiInstance.findFlows(processId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findFlows");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process related to the flow |
 **page** | **Integer**| Page numbers to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per Page | [optional] [default to 15]

### Return type

[**FlowCollection**](FlowCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findGatewayById"></a>
# **findGatewayById**
> GatewayItem findGatewayById(processId, gatewayId)



This method retrieves a gateway based on its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process to return
String gatewayId = "gatewayId_example"; // String | ID of gateway to return
try {
    GatewayItem result = apiInstance.findGatewayById(processId, gatewayId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findGatewayById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process to return |
 **gatewayId** | **String**| ID of gateway to return |

### Return type

[**GatewayItem**](GatewayItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findGateways"></a>
# **findGateways**
> GatewayCollection findGateways(processId, page, perPage)



This method retrieves all existing gateways.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process related to the gateway
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per page
try {
    GatewayCollection result = apiInstance.findGateways(processId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findGateways");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process related to the gateway |
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per page | [optional] [default to 15]

### Return type

[**GatewayCollection**](GatewayCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findGroupById"></a>
# **findGroupById**
> GroupItem findGroupById(id)



This method retrieves a group using its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of group to return
try {
    GroupItem result = apiInstance.findGroupById(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findGroupById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of group to return |

### Return type

[**GroupItem**](GroupItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findGroups"></a>
# **findGroups**
> GroupCollection findGroups(page, perPage)



This method retrieves all existing groups.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per Page
try {
    GroupCollection result = apiInstance.findGroups(page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findGroups");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per Page | [optional] [default to 15]

### Return type

[**GroupCollection**](GroupCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findInputOutputById"></a>
# **findInputOutputById**
> InputOutputItem findInputOutputById(processId, taskId, inputoutputUid)



This method retrieves an Input/Output object using its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID related to the Input/Output object
String taskId = "taskId_example"; // String | Task instance ID related to the Input/Output object
String inputoutputUid = "inputoutputUid_example"; // String | ID of Input/Output to return
try {
    InputOutputItem result = apiInstance.findInputOutputById(processId, taskId, inputoutputUid);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findInputOutputById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID related to the Input/Output object |
 **taskId** | **String**| Task instance ID related to the Input/Output object |
 **inputoutputUid** | **String**| ID of Input/Output to return |

### Return type

[**InputOutputItem**](InputOutputItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findInputOutputs"></a>
# **findInputOutputs**
> InputOutputCollection findInputOutputs(processId, taskId, page, perPage)



This method retrieves all existing Input/Output objects in the related task instance.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID related to Input/Output object
String taskId = "taskId_example"; // String | Task instance ID related to Input/Output object
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per page
try {
    InputOutputCollection result = apiInstance.findInputOutputs(processId, taskId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findInputOutputs");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID related to Input/Output object |
 **taskId** | **String**| Task instance ID related to Input/Output object |
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per page | [optional] [default to 15]

### Return type

[**InputOutputCollection**](InputOutputCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findInstanceById"></a>
# **findInstanceById**
> InstanceItem findInstanceById(processId, instanceId)



This method retrieves an instance using its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process to return
String instanceId = "instanceId_example"; // String | ID of instance to return
try {
    InstanceItem result = apiInstance.findInstanceById(processId, instanceId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findInstanceById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process to return |
 **instanceId** | **String**| ID of instance to return |

### Return type

[**InstanceItem**](InstanceItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findInstances"></a>
# **findInstances**
> InstanceCollection findInstances(processId, page, perPage)



This method retrieves related to the process using  the Process ID

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID related to the instances
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per page
try {
    InstanceCollection result = apiInstance.findInstances(processId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findInstances");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID related to the instances |
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per page | [optional] [default to 15]

### Return type

[**InstanceCollection**](InstanceCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findProcessById"></a>
# **findProcessById**
> ProcessItem findProcessById(id)



This method retrieves a process using its ID

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of process to return
try {
    ProcessItem result = apiInstance.findProcessById(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findProcessById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of process to return |

### Return type

[**ProcessItem**](ProcessItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findProcesses"></a>
# **findProcesses**
> ProcessCollection findProcesses(page, perPage)



This method retrieves all existing processes.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per page
try {
    ProcessCollection result = apiInstance.findProcesses(page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findProcesses");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per page | [optional] [default to 15]

### Return type

[**ProcessCollection**](ProcessCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findTaskById"></a>
# **findTaskById**
> TaskItem findTaskById(processId, taskId)



This method is retrieves a task using its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process to return
String taskId = "taskId_example"; // String | ID of task to return
try {
    TaskItem result = apiInstance.findTaskById(processId, taskId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findTaskById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process to return |
 **taskId** | **String**| ID of task to return |

### Return type

[**TaskItem**](TaskItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findTaskConnectorById"></a>
# **findTaskConnectorById**
> TaskConnector1 findTaskConnectorById(processId, taskId, connectorId)



This method is intended for retrieving an Task connector based on it&#39;s ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to fetch
String taskId = "taskId_example"; // String | ID of Task to fetch
String connectorId = "connectorId_example"; // String | ID of TaskConnector to fetch
try {
    TaskConnector1 result = apiInstance.findTaskConnectorById(processId, taskId, connectorId);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findTaskConnectorById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to fetch |
 **taskId** | **String**| ID of Task to fetch |
 **connectorId** | **String**| ID of TaskConnector to fetch |

### Return type

[**TaskConnector1**](TaskConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findTaskConnectors"></a>
# **findTaskConnectors**
> TaskConnectorsCollection findTaskConnectors(processId, taskId, page, perPage)



This method returns all Task connectors related to the run Process and Task.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to fetch
String taskId = "taskId_example"; // String | ID of Task to fetch
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per Page
try {
    TaskConnectorsCollection result = apiInstance.findTaskConnectors(processId, taskId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findTaskConnectors");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to fetch |
 **taskId** | **String**| ID of Task to fetch |
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per Page | [optional] [default to 15]

### Return type

[**TaskConnectorsCollection**](TaskConnectorsCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findTaskInstanceById"></a>
# **findTaskInstanceById**
> InlineResponse200 findTaskInstanceById(taskInstanceId, page, perPage)



This method retrieves a task instance based on its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String taskInstanceId = "taskInstanceId_example"; // String | ID of task instance to return
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per page
try {
    InlineResponse200 result = apiInstance.findTaskInstanceById(taskInstanceId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findTaskInstanceById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **taskInstanceId** | **String**| ID of task instance to return |
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per page | [optional] [default to 15]

### Return type

[**InlineResponse200**](InlineResponse200.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findTaskInstances"></a>
# **findTaskInstances**
> TaskInstanceCollection findTaskInstances(page, perPage)



This method retrieves all existing task instances

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per page
try {
    TaskInstanceCollection result = apiInstance.findTaskInstances(page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findTaskInstances");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per page | [optional] [default to 15]

### Return type

[**TaskInstanceCollection**](TaskInstanceCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findTasks"></a>
# **findTasks**
> TaskCollection findTasks(processId, page, perPage)



This method is intended for returning a list of all Tasks related to the process

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process relative to task
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per Page
try {
    TaskCollection result = apiInstance.findTasks(processId, page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findTasks");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process relative to task |
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per Page | [optional] [default to 15]

### Return type

[**TaskCollection**](TaskCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findUserById"></a>
# **findUserById**
> UserItem findUserById(id)



This method returns a user using its ID.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of the user to return
try {
    UserItem result = apiInstance.findUserById(id);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findUserById");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of the user to return |

### Return type

[**UserItem**](UserItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="findUsers"></a>
# **findUsers**
> UserCollection findUsers(page, perPage)



This method returs all existing users in the system.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per page
try {
    UserCollection result = apiInstance.findUsers(page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#findUsers");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per page | [optional] [default to 15]

### Return type

[**UserCollection**](UserCollection.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="importBpmnFile"></a>
# **importBpmnFile**
> ProcessCollection1 importBpmnFile(bpmnImportItem)



This method imports BPMN files. A new process is created when import is successful.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
BpmnImportItem bpmnImportItem = new BpmnImportItem(); // BpmnImportItem | JSON API with the BPMN file to import
try {
    ProcessCollection1 result = apiInstance.importBpmnFile(bpmnImportItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#importBpmnFile");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bpmnImportItem** | [**BpmnImportItem**](BpmnImportItem.md)| JSON API with the BPMN file to import |

### Return type

[**ProcessCollection1**](ProcessCollection1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="myselfUser"></a>
# **myselfUser**
> UserItem myselfUser(page, perPage)



This method returns user information using a token

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
Integer page = 1; // Integer | Page number to fetch
Integer perPage = 15; // Integer | Amount of items per page
try {
    UserItem result = apiInstance.myselfUser(page, perPage);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#myselfUser");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **Integer**| Page number to fetch | [optional] [default to 1]
 **perPage** | **Integer**| Amount of items per page | [optional] [default to 15]

### Return type

[**UserItem**](UserItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="removeGroupsFromTask"></a>
# **removeGroupsFromTask**
> ResultSuccess removeGroupsFromTask(processId, taskId, taskRemoveGroupsItem)



This method removes groups from a task

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID
String taskId = "taskId_example"; // String | Task ID
TaskRemoveGroupsItem taskRemoveGroupsItem = new TaskRemoveGroupsItem(); // TaskRemoveGroupsItem | JSON API response with Groups IDs to remove
try {
    ResultSuccess result = apiInstance.removeGroupsFromTask(processId, taskId, taskRemoveGroupsItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#removeGroupsFromTask");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID |
 **taskId** | **String**| Task ID |
 **taskRemoveGroupsItem** | [**TaskRemoveGroupsItem**](TaskRemoveGroupsItem.md)| JSON API response with Groups IDs to remove |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="removeUsersFromGroup"></a>
# **removeUsersFromGroup**
> ResultSuccess removeUsersFromGroup(id, groupRemoveUsersItem)



This method removes one or more users from a group.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of group to be modified
GroupRemoveUsersItem groupRemoveUsersItem = new GroupRemoveUsersItem(); // GroupRemoveUsersItem | JSON API response with Users IDs to remove
try {
    ResultSuccess result = apiInstance.removeUsersFromGroup(id, groupRemoveUsersItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#removeUsersFromGroup");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of group to be modified |
 **groupRemoveUsersItem** | [**GroupRemoveUsersItem**](GroupRemoveUsersItem.md)| JSON API response with Users IDs to remove |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="syncGroupsToTask"></a>
# **syncGroupsToTask**
> ResultSuccess syncGroupsToTask(processId, taskId, taskSyncGroupsItem)



This method synchronizes a one or more groups with a task.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID
String taskId = "taskId_example"; // String | ID of task to modify
TaskSyncGroupsItem taskSyncGroupsItem = new TaskSyncGroupsItem(); // TaskSyncGroupsItem | JSON API response with groups IDs to sync
try {
    ResultSuccess result = apiInstance.syncGroupsToTask(processId, taskId, taskSyncGroupsItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#syncGroupsToTask");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID |
 **taskId** | **String**| ID of task to modify |
 **taskSyncGroupsItem** | [**TaskSyncGroupsItem**](TaskSyncGroupsItem.md)| JSON API response with groups IDs to sync |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="syncUsersToGroup"></a>
# **syncUsersToGroup**
> ResultSuccess syncUsersToGroup(id, groupSyncUsersItem)



This method synchronizes one or more users with a group.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of group to be modifieded
GroupSyncUsersItem groupSyncUsersItem = new GroupSyncUsersItem(); // GroupSyncUsersItem | JSON API with array of users IDs to sync
try {
    ResultSuccess result = apiInstance.syncUsersToGroup(id, groupSyncUsersItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#syncUsersToGroup");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of group to be modifieded |
 **groupSyncUsersItem** | [**GroupSyncUsersItem**](GroupSyncUsersItem.md)| JSON API with array of users IDs to sync |

### Return type

[**ResultSuccess**](ResultSuccess.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateClient"></a>
# **updateClient**
> ClientItem updateClient(userId, clientId, clientUpdateItem)



This method updates an existing Oauth client.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String userId = "userId_example"; // String | ID of user to retrieve
String clientId = "clientId_example"; // String | ID of client to retrieve
ClientUpdateItem clientUpdateItem = new ClientUpdateItem(); // ClientUpdateItem | Client object to edit
try {
    ClientItem result = apiInstance.updateClient(userId, clientId, clientUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateClient");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userId** | **String**| ID of user to retrieve |
 **clientId** | **String**| ID of client to retrieve |
 **clientUpdateItem** | [**ClientUpdateItem**](ClientUpdateItem.md)| Client object to edit |

### Return type

[**ClientItem**](ClientItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateEvent"></a>
# **updateEvent**
> EventItem updateEvent(processId, eventId, eventUpdateItem)



This method updates an existing event

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process to retrieve
String eventId = "eventId_example"; // String | ID of event to retrieve
EventUpdateItem eventUpdateItem = new EventUpdateItem(); // EventUpdateItem | Event object to edit
try {
    EventItem result = apiInstance.updateEvent(processId, eventId, eventUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateEvent");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process to retrieve |
 **eventId** | **String**| ID of event to retrieve |
 **eventUpdateItem** | [**EventUpdateItem**](EventUpdateItem.md)| Event object to edit |

### Return type

[**EventItem**](EventItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateEventConnector"></a>
# **updateEventConnector**
> EventConnector1 updateEventConnector(processId, eventId, connectorId, eventConnectorUpdateItem)



This method lets update the existing Event connector with new parameters values

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to fetch
String eventId = "eventId_example"; // String | ID of Event to fetch
String connectorId = "connectorId_example"; // String | ID of Event Connector to fetch
EventConnectorUpdateItem eventConnectorUpdateItem = new EventConnectorUpdateItem(); // EventConnectorUpdateItem | EventConnector object to edit
try {
    EventConnector1 result = apiInstance.updateEventConnector(processId, eventId, connectorId, eventConnectorUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateEventConnector");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to fetch |
 **eventId** | **String**| ID of Event to fetch |
 **connectorId** | **String**| ID of Event Connector to fetch |
 **eventConnectorUpdateItem** | [**EventConnectorUpdateItem**](EventConnectorUpdateItem.md)| EventConnector object to edit |

### Return type

[**EventConnector1**](EventConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateFlow"></a>
# **updateFlow**
> FlowItem updateFlow(processId, flowId, flowUpdateItem)



This method updates an existing flow.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process to retrieve
String flowId = "flowId_example"; // String | ID of flow to retrieve
FlowUpdateItem flowUpdateItem = new FlowUpdateItem(); // FlowUpdateItem | Flow object to edit
try {
    FlowItem result = apiInstance.updateFlow(processId, flowId, flowUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateFlow");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process to retrieve |
 **flowId** | **String**| ID of flow to retrieve |
 **flowUpdateItem** | [**FlowUpdateItem**](FlowUpdateItem.md)| Flow object to edit |

### Return type

[**FlowItem**](FlowItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateGateway"></a>
# **updateGateway**
> GatewayItem updateGateway(processId, gatewayId, gatewayUpdateItem)



This method updates an existing gateway.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of process to retrieve
String gatewayId = "gatewayId_example"; // String | ID of gateway to retrieve
GatewayUpdateItem gatewayUpdateItem = new GatewayUpdateItem(); // GatewayUpdateItem | Gateway object to edit
try {
    GatewayItem result = apiInstance.updateGateway(processId, gatewayId, gatewayUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateGateway");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of process to retrieve |
 **gatewayId** | **String**| ID of gateway to retrieve |
 **gatewayUpdateItem** | [**GatewayUpdateItem**](GatewayUpdateItem.md)| Gateway object to edit |

### Return type

[**GatewayItem**](GatewayItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateGroup"></a>
# **updateGroup**
> GroupItem updateGroup(id, groupUpdateItem)



This method updates an existing group.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of group to retrieve
GroupUpdateItem groupUpdateItem = new GroupUpdateItem(); // GroupUpdateItem | Group object to edit
try {
    GroupItem result = apiInstance.updateGroup(id, groupUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateGroup");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of group to retrieve |
 **groupUpdateItem** | [**GroupUpdateItem**](GroupUpdateItem.md)| Group object to edit |

### Return type

[**GroupItem**](GroupItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateInputOutput"></a>
# **updateInputOutput**
> InputOutputItem updateInputOutput(processId, taskId, inputoutputUid, inputOutputUpdateItem)



This method updates an existing Input/Output object.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | Process ID related to the Input/Output object
String taskId = "taskId_example"; // String | Task instance ID related to the Input/Output object
String inputoutputUid = "inputoutputUid_example"; // String | ID of Input/Output to retrieve
InputOutputUpdateItem inputOutputUpdateItem = new InputOutputUpdateItem(); // InputOutputUpdateItem | Input/Output object to edit
try {
    InputOutputItem result = apiInstance.updateInputOutput(processId, taskId, inputoutputUid, inputOutputUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateInputOutput");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| Process ID related to the Input/Output object |
 **taskId** | **String**| Task instance ID related to the Input/Output object |
 **inputoutputUid** | **String**| ID of Input/Output to retrieve |
 **inputOutputUpdateItem** | [**InputOutputUpdateItem**](InputOutputUpdateItem.md)| Input/Output object to edit |

### Return type

[**InputOutputItem**](InputOutputItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateInstance"></a>
# **updateInstance**
> InstanceItem updateInstance(processId, instanceId, instanceUpdateItem)



This method updates  an existing instance.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to retrieve
String instanceId = "instanceId_example"; // String | ID of Instance to retrieve
InstanceUpdateItem instanceUpdateItem = new InstanceUpdateItem(); // InstanceUpdateItem | Instance object to edit
try {
    InstanceItem result = apiInstance.updateInstance(processId, instanceId, instanceUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateInstance");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to retrieve |
 **instanceId** | **String**| ID of Instance to retrieve |
 **instanceUpdateItem** | [**InstanceUpdateItem**](InstanceUpdateItem.md)| Instance object to edit |

### Return type

[**InstanceItem**](InstanceItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateProcess"></a>
# **updateProcess**
> ProcessItem updateProcess(id, processUpdateItem)



This method updates an existing process.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of process to retrieve
ProcessUpdateItem processUpdateItem = new ProcessUpdateItem(); // ProcessUpdateItem | Process object to edit
try {
    ProcessItem result = apiInstance.updateProcess(id, processUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateProcess");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of process to retrieve |
 **processUpdateItem** | [**ProcessUpdateItem**](ProcessUpdateItem.md)| Process object to edit |

### Return type

[**ProcessItem**](ProcessItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateTask"></a>
# **updateTask**
> TaskItem updateTask(processId, taskId, taskUpdateItem)



This method is intended for updating an existing task.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to fetch
String taskId = "taskId_example"; // String | ID of Task to fetch
TaskUpdateItem taskUpdateItem = new TaskUpdateItem(); // TaskUpdateItem | Task object to edit
try {
    TaskItem result = apiInstance.updateTask(processId, taskId, taskUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateTask");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to fetch |
 **taskId** | **String**| ID of Task to fetch |
 **taskUpdateItem** | [**TaskUpdateItem**](TaskUpdateItem.md)| Task object to edit |

### Return type

[**TaskItem**](TaskItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateTaskConnector"></a>
# **updateTaskConnector**
> TaskConnector1 updateTaskConnector(processId, taskId, connectorId, taskConnectorUpdateItem)



This method lets update the existing Task connector with new parameters values

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String processId = "processId_example"; // String | ID of Process to fetch
String taskId = "taskId_example"; // String | ID of Task to fetch
String connectorId = "connectorId_example"; // String | ID of Task Connector to fetch
TaskConnectorUpdateItem taskConnectorUpdateItem = new TaskConnectorUpdateItem(); // TaskConnectorUpdateItem | TaskConnector object to edit
try {
    TaskConnector1 result = apiInstance.updateTaskConnector(processId, taskId, connectorId, taskConnectorUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateTaskConnector");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **processId** | **String**| ID of Process to fetch |
 **taskId** | **String**| ID of Task to fetch |
 **connectorId** | **String**| ID of Task Connector to fetch |
 **taskConnectorUpdateItem** | [**TaskConnectorUpdateItem**](TaskConnectorUpdateItem.md)| TaskConnector object to edit |

### Return type

[**TaskConnector1**](TaskConnector1.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateTaskInstance"></a>
# **updateTaskInstance**
> InlineResponse200 updateTaskInstance(taskInstanceId, taskInstanceUpdateItem)



This method updates an existing task instance.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String taskInstanceId = "taskInstanceId_example"; // String | ID of task instance to retrieve
TaskInstanceUpdateItem taskInstanceUpdateItem = new TaskInstanceUpdateItem(); // TaskInstanceUpdateItem | Task Instance object to update
try {
    InlineResponse200 result = apiInstance.updateTaskInstance(taskInstanceId, taskInstanceUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateTaskInstance");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **taskInstanceId** | **String**| ID of task instance to retrieve |
 **taskInstanceUpdateItem** | [**TaskInstanceUpdateItem**](TaskInstanceUpdateItem.md)| Task Instance object to update |

### Return type

[**InlineResponse200**](InlineResponse200.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json

<a name="updateUser"></a>
# **updateUser**
> UserItem updateUser(id, userUpdateItem)



This method updates an existing user.

### Example
```java
// Import classes:
//import processmaker.pmio.ApiClient;
//import processmaker.pmio.ApiException;
//import processmaker.pmio.Configuration;
//import processmaker.pmio.auth.*;
//import processmaker.pmio.api.ProcessmakerApi;

ApiClient defaultClient = Configuration.getDefaultApiClient();

// Configure OAuth2 access token for authorization: PasswordGrant
OAuth PasswordGrant = (OAuth) defaultClient.getAuthentication("PasswordGrant");
PasswordGrant.setAccessToken("YOUR ACCESS TOKEN");

ProcessmakerApi apiInstance = new ProcessmakerApi();
String id = "id_example"; // String | ID of user to retrieve
UserUpdateItem userUpdateItem = new UserUpdateItem(); // UserUpdateItem | User object for update
try {
    UserItem result = apiInstance.updateUser(id, userUpdateItem);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling ProcessmakerApi#updateUser");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **String**| ID of user to retrieve |
 **userUpdateItem** | [**UserUpdateItem**](UserUpdateItem.md)| User object for update |

### Return type

[**UserItem**](UserItem.md)

### Authorization

[PasswordGrant](../README.md#PasswordGrant)

### HTTP request headers

 - **Content-Type**: application/vnd.api+json
 - **Accept**: application/vnd.api+json



# InstanceAttributes

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **String** |  | 
**description** | **String** |  |  [optional]
**processId** | **String** |  | 
**parentInstanceId** | **String** |  |  [optional]
**initUserId** | **String** |  |  [optional]
**pin** | **String** |  |  [optional]
**duration** | **Integer** |  |  [optional]
**status** | [**StatusEnum**](#StatusEnum) |  | 
**createdAt** | **String** |  |  [optional]
**updatedAt** | **String** |  |  [optional]


<a name="StatusEnum"></a>
## Enum: StatusEnum
Name | Value
---- | -----
RUNNING | &quot;RUNNING&quot;
TODO | &quot;TODO&quot;
PAUSED | &quot;PAUSED&quot;
COMPLETED | &quot;COMPLETED&quot;
CANCELLED | &quot;CANCELLED&quot;




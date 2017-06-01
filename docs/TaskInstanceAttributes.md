
# TaskInstanceAttributes

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**taskId** | **String** |  | 
**instanceId** | **String** |  | 
**groupId** | **String** |  |  [optional]
**userId** | **String** |  |  [optional]
**status** | [**StatusEnum**](#StatusEnum) |  | 
**priority** | [**PriorityEnum**](#PriorityEnum) |  | 
**delegateDate** | **String** |  |  [optional]
**startDate** | **String** |  |  [optional]
**finishDate** | **String** |  |  [optional]
**taskDueDate** | **String** |  |  [optional]
**riskDate** | **String** |  |  [optional]
**duration** | **Integer** |  |  [optional]
**instanceOverduePercentage** | **Double** |  |  [optional]
**data** | **String** |  |  [optional]
**content** | **String** |  |  [optional]
**createdAt** | **String** |  |  [optional]
**updatedAt** | **String** |  |  [optional]


<a name="StatusEnum"></a>
## Enum: StatusEnum
Name | Value
---- | -----
INITIAL | &quot;INITIAL&quot;
DELEGATED | &quot;DELEGATED&quot;
STARTED | &quot;STARTED&quot;
CANCELLED | &quot;CANCELLED&quot;
FINISHED | &quot;FINISHED&quot;
COMPLETE | &quot;COMPLETE&quot;
PAUSED | &quot;PAUSED&quot;


<a name="PriorityEnum"></a>
## Enum: PriorityEnum
Name | Value
---- | -----
_1 | &quot;1&quot;
_2 | &quot;2&quot;
_3 | &quot;3&quot;
_4 | &quot;4&quot;
_5 | &quot;5&quot;




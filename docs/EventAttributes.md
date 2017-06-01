
# EventAttributes

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **String** |  | 
**description** | **String** |  |  [optional]
**processId** | **String** |  | 
**messageId** | **Integer** |  |  [optional]
**type** | [**TypeEnum**](#TypeEnum) |  | 
**definition** | [**DefinitionEnum**](#DefinitionEnum) |  | 
**interrupting** | **Boolean** |  |  [optional]
**condition** | **String** |  |  [optional]
**time** | **String** |  |  [optional]
**duration** | **String** |  |  [optional]
**cycle** | **String** |  |  [optional]
**attachedToTaskId** | **String** |  |  [optional]
**createdAt** | **String** |  |  [optional]
**updatedAt** | **String** |  |  [optional]


<a name="TypeEnum"></a>
## Enum: TypeEnum
Name | Value
---- | -----
START | &quot;START&quot;
END | &quot;END&quot;
INTERMEDIATE_CATCH | &quot;INTERMEDIATE_CATCH&quot;
INTERMEDIATE_THROW | &quot;INTERMEDIATE_THROW&quot;
BOUNDARY | &quot;BOUNDARY&quot;
IMPLICIT_THROW | &quot;IMPLICIT_THROW&quot;


<a name="DefinitionEnum"></a>
## Enum: DefinitionEnum
Name | Value
---- | -----
NONE | &quot;NONE&quot;
CANCEL | &quot;CANCEL&quot;
COMPENSATION | &quot;COMPENSATION&quot;
ERROR | &quot;ERROR&quot;
ESCALATION | &quot;ESCALATION&quot;
MESSAGE | &quot;MESSAGE&quot;
LINK | &quot;LINK&quot;
SIGNAL | &quot;SIGNAL&quot;
TERMINATE | &quot;TERMINATE&quot;
TIMER | &quot;TIMER&quot;




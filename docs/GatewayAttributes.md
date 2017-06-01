
# GatewayAttributes

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **String** |  |  [optional]
**description** | **String** |  |  [optional]
**processId** | **String** |  | 
**type** | [**TypeEnum**](#TypeEnum) |  | 
**direction** | [**DirectionEnum**](#DirectionEnum) |  |  [optional]
**createdAt** | **String** |  |  [optional]
**updatedAt** | **String** |  |  [optional]


<a name="TypeEnum"></a>
## Enum: TypeEnum
Name | Value
---- | -----
EXCLUSIVE | &quot;EXCLUSIVE&quot;
INCLUSIVE | &quot;INCLUSIVE&quot;
PARALLEL | &quot;PARALLEL&quot;
EVENT | &quot;EVENT&quot;


<a name="DirectionEnum"></a>
## Enum: DirectionEnum
Name | Value
---- | -----
DIVERGENT | &quot;DIVERGENT&quot;
CONVERGENT | &quot;CONVERGENT&quot;
MIXED | &quot;MIXED&quot;




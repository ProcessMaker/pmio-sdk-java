
# FlowAttributes

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **String** |  |  [optional]
**description** | **String** |  |  [optional]
**processId** | **String** |  | 
**fromObjectId** | **String** |  | 
**fromObjectType** | **String** |  | 
**toObjectId** | **String** |  | 
**toObjectType** | **String** |  | 
**type** | [**TypeEnum**](#TypeEnum) |  | 
**condition** | **String** |  |  [optional]
**_default** | **Boolean** |  | 
**optional** | **Boolean** |  | 
**createdAt** | **String** |  |  [optional]
**updatedAt** | **String** |  |  [optional]


<a name="TypeEnum"></a>
## Enum: TypeEnum
Name | Value
---- | -----
SEQUENTIAL | &quot;SEQUENTIAL&quot;
EVALUATE | &quot;EVALUATE&quot;
SELECT | &quot;SELECT&quot;
PARALLEL | &quot;PARALLEL&quot;
PARALLEL_BY_EVALUATION | &quot;PARALLEL-BY-EVALUATION&quot;
SEC_JOIN | &quot;SEC-JOIN&quot;
DISCRIMINATOR | &quot;DISCRIMINATOR&quot;




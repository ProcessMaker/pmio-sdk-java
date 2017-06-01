
# ProcessAttributes

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **String** |  | 
**description** | **String** |  |  [optional]
**parentProcessId** | **String** |  |  [optional]
**status** | [**StatusEnum**](#StatusEnum) |  | 
**durationBy** | [**DurationByEnum**](#DurationByEnum) |  | 
**type** | [**TypeEnum**](#TypeEnum) |  | 
**assignment** | **Boolean** |  |  [optional]
**designAccess** | [**DesignAccessEnum**](#DesignAccessEnum) |  | 
**showMap** | **Boolean** |  |  [optional]
**showMessage** | **Boolean** |  |  [optional]
**showDelegate** | **Boolean** |  |  [optional]
**showDynaform** | **Boolean** |  |  [optional]
**categoryId** | **String** |  |  [optional]
**subCategoryId** | **String** |  |  [optional]
**createUserId** | **String** |  |  [optional]
**debug** | **Boolean** |  |  [optional]
**dynaformSummaryId** | **String** |  |  [optional]
**createdAt** | **String** |  |  [optional]
**updatedAt** | **String** |  |  [optional]


<a name="StatusEnum"></a>
## Enum: StatusEnum
Name | Value
---- | -----
ACTIVE | &quot;ACTIVE&quot;
INACTIVE | &quot;INACTIVE&quot;
DISABLED | &quot;DISABLED&quot;


<a name="DurationByEnum"></a>
## Enum: DurationByEnum
Name | Value
---- | -----
WORKING_DAYS | &quot;WORKING_DAYS&quot;
CALENDAR_DAYS | &quot;CALENDAR_DAYS&quot;


<a name="TypeEnum"></a>
## Enum: TypeEnum
Name | Value
---- | -----
NORMAL | &quot;NORMAL&quot;
SUB_PROCESS | &quot;SUB_PROCESS&quot;


<a name="DesignAccessEnum"></a>
## Enum: DesignAccessEnum
Name | Value
---- | -----
PUBLIC | &quot;PUBLIC&quot;
PRIVATE | &quot;PRIVATE&quot;




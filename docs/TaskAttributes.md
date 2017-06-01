
# TaskAttributes

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **String** |  | 
**description** | **String** |  |  [optional]
**processId** | **String** |  | 
**type** | [**TypeEnum**](#TypeEnum) |  | 
**assignType** | [**AssignTypeEnum**](#AssignTypeEnum) |  | 
**priorityVariable** | **String** |  |  [optional]
**assignVariable** | **String** |  |  [optional]
**groupVariable** | **String** |  |  [optional]
**miInstanceVariable** | **String** |  |  [optional]
**miCompleteVariable** | **String** |  |  [optional]
**transferFly** | **Boolean** |  | 
**canUpload** | **Boolean** |  | 
**viewUpload** | **Boolean** |  | 
**viewAdditionalDocumentation** | **Boolean** |  | 
**start** | **Boolean** |  | 
**sendLastEmail** | **Boolean** |  | 
**derivationScreenTpl** | **String** |  |  [optional]
**selfserviceTimeout** | **Integer** |  | 
**selfserviceTime** | **String** |  |  [optional]
**selfserviceTimeUnit** | **String** |  |  [optional]
**selfserviceExecution** | **String** |  |  [optional]
**lastAssignedUserId** | **String** |  |  [optional]
**script** | **String** |  |  [optional]
**createdAt** | **String** |  |  [optional]
**updatedAt** | **String** |  |  [optional]


<a name="TypeEnum"></a>
## Enum: TypeEnum
Name | Value
---- | -----
NORMAL | &quot;NORMAL&quot;
ADHOC | &quot;ADHOC&quot;
SUBPROCESS | &quot;SUBPROCESS&quot;
HIDDEN | &quot;HIDDEN&quot;
GATEWAYTOGATEWAY | &quot;GATEWAYTOGATEWAY&quot;
WEBENTRYEVENT | &quot;WEBENTRYEVENT&quot;
END_MESSAGE_EVENT | &quot;END-MESSAGE-EVENT&quot;
START_MESSAGE_EVENT | &quot;START-MESSAGE-EVENT&quot;
INTERMEDIATE_THROW_MESSAGE_EVENT | &quot;INTERMEDIATE-THROW-MESSAGE-EVENT&quot;
INTERMEDIATE_CATCH_MESSAGE_EVENT | &quot;INTERMEDIATE-CATCH-MESSAGE-EVENT&quot;
SCRIPT_TASK | &quot;SCRIPT-TASK&quot;
SERVICE_TASK | &quot;SERVICE-TASK&quot;
USER_TASK | &quot;USER-TASK&quot;
START_TIMER_EVENT | &quot;START-TIMER-EVENT&quot;
INTERMEDIATE_CATCH_TIMER_EVENT | &quot;INTERMEDIATE-CATCH-TIMER-EVENT&quot;
END_EMAIL_EVENT | &quot;END-EMAIL-EVENT&quot;
INTERMEDIATE_THROW_EMAIL_EVENT | &quot;INTERMEDIATE-THROW-EMAIL-EVENT&quot;


<a name="AssignTypeEnum"></a>
## Enum: AssignTypeEnum
Name | Value
---- | -----
CYCLIC | &quot;CYCLIC&quot;
MANUAL | &quot;MANUAL&quot;
EVALUATE | &quot;EVALUATE&quot;
REPORT_TO | &quot;REPORT_TO&quot;
SELF_SERVICE | &quot;SELF_SERVICE&quot;
STATIC_MI | &quot;STATIC_MI&quot;
CANCEL_MI | &quot;CANCEL_MI&quot;
MULTIPLE_INSTANCE | &quot;MULTIPLE_INSTANCE&quot;
MULTIPLE_INSTANCE_VALUE_BASED | &quot;MULTIPLE_INSTANCE_VALUE_BASED&quot;




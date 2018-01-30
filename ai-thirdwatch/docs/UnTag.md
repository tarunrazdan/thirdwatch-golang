# UnTag

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | The user&#39;s account ID according to your systems. Note that user IDs are case sensitive. | [optional] [default to null]
**AbuseType** | **string** | The type of abuse for which you want to untag user. It&#39;s important to send a untag specific to the type of abuse. You&#39;ll end up with more accurate results this way. e.g. _paymentAbuse, _contentAbuse, _promotionAbuse, _accountAbuse If you wants to untag from all type of abuses than don&#39;t send this parameter. | [optional] [default to null]
**Analyst** | **string** | Unique identifier (e.g. email address) of the analyst who applied the label. Useful for tracking purposes after the fact. | [optional] [default to null]
**CustomInfo** | [**CustomInfo**](CustomInfo.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



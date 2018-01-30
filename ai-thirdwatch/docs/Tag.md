# Tag

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | The user&#39;s account ID according to your systems. Note that user IDs are case sensitive. | [optional] [default to null]
**IsBad** | **bool** | Indicates whether a user is engaging in behavior deemed harmful to your business. Set to true if the user is engaging in abusive activity. Set to false if the user is engaging in valid activity. | [optional] [default to null]
**AbuseType** | **string** | The type of abuse for which you want to send a tag. It&#39;s important to send a tag specific to the type of abuse the user is committing so that thirdwatch can learn about specific patterns of behavior. You&#39;ll end up with more accurate results this way. e.g. _paymentAbuse, _contentAbuse, _promotionAbuse, _accountAbuse | [optional] [default to null]
**Description** | **string** | The text content of the tag.Useful as annotation on why the label was added. | [optional] [default to null]
**Source** | **string** | String describing the original source of the tag information (e.g. payment gateway, manual review, etc.). | [optional] [default to null]
**Analyst** | **string** | Unique identifier (e.g. email address) of the analyst who applied the label. Useful for tracking purposes after the fact. | [optional] [default to null]
**CustomInfo** | [**CustomInfo**](CustomInfo.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



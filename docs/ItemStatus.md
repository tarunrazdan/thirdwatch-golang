# ItemStatus

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | The user&#39;s account ID according to your systems. Note that user IDs are case sensitive. | [optional] [default to null]
**SessionId** | **string** | The user&#39;s current session ID, used to tie a user&#39;s action before and after login or account creation. Required if no user_id values is provided. | [optional] [default to null]
**OrderId** | **string** | The ID for the order that this chargeback is filed against. This field is not required if this chargeback was filed against a transaction with no _orderId. | [optional] [default to null]
**ItemId** | **string** | The item&#39;s unique identifier according to your systems. Use the same ID that you would use to look up items on your website&#39;s database. | [optional] [default to null]
**ItemStatus** | **string** | Indicates the high-level state of the order. e.g. _approved, _canceled, _held, _fulfilled, _returned, _rto | [optional] [default to null]
**Reason** | **string** | The reason for a cancellation. e.g. _paymentRisk, _abuse, _policy, _other | [optional] [default to null]
**ShippingCost** | **string** | if _approved or _fulfilled than pass the shipping cost. e.g. \&quot;50\&quot; | [optional] [default to null]
**TrackingNumber** | **string** | if _approved or _fulfilled than pass the tracking number. e.g. \&quot;55327470\&quot; | [optional] [default to null]
**TrackingMethod** | **string** | if _approved or _fulfilled than pass the tracking url. e.g. \&quot;http://fedex.com/track?q&#x3D;abc123\&quot; | [optional] [default to null]
**Source** | **string** | The source of a decision. e.g. _automated, _manualReview\&quot; | [optional] [default to null]
**Analyst** | **string** | The analyst who made the decision, if manual. | [optional] [default to null]
**Description** | **string** | Any additional information about this order status change. | [optional] [default to null]
**CustomInfo** | [**CustomInfo**](CustomInfo.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



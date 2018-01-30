# ReportItem

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | The user&#39;s account ID according to your systems. Note that user IDs are case sensitive. | [optional] [default to null]
**SessionId** | **string** | The user&#39;s current session ID, used to tie a user&#39;s action before and after login or account creation. Required if no user_id values is provided. | [optional] [default to null]
**ItemId** | **string** | The unique ID for the item that is being reported. Note - item IDs are case sensitive. | [optional] [default to null]
**DeviceIp** | **string** | IP address of the request made by the user. Recommended for historical backfills and customers with mobile apps. | [optional] [default to null]
**OriginTimestamp** | **string** | Represents the time the event occured in your system. Send as a UNIX timestamp in milliseconds in string. | [optional] [default to null]
**UserEmail** | **string** | Email of the user creating this order. Note - If the user&#39;s email is also their account ID in your system, set both the userId and userEmail fields to their email address. | [optional] [default to null]
**CustomInfo** | [**CustomInfo**](CustomInfo.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



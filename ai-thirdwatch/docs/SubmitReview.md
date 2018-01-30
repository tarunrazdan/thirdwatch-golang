# SubmitReview

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | The user&#39;s account ID according to your systems. Note that user IDs are case sensitive. | [optional] [default to null]
**SessionId** | **string** | The user&#39;s current session ID, used to tie a user&#39;s action before and after login or account creation. Required if no user_id values is provided. | [optional] [default to null]
**DeviceIp** | **string** | IP address of the request made by the user. Recommended for historical backfills and customers with mobile apps. | [optional] [default to null]
**OriginTimestamp** | **string** | Represents the time the event occured in your system. Send as a UNIX timestamp in milliseconds in string. | [optional] [default to null]
**ReviewTitle** | **string** | The title of review submitted. | [optional] [default to null]
**ReviewContent** | **string** | The text content of review submitted. | [optional] [default to null]
**ItemId** | **string** | The ID of the product or service being reviewed. | [optional] [default to null]
**SubmissionStatus** | **string** | If reviews in your system must be approved, use _submissionStatus to represent the status of the review. e.g. _success, _failure, _pending | [optional] [default to null]
**Rating** | **string** | The rating provided by the user. e.g. \&quot;4\&quot; | [optional] [default to null]
**CustomInfo** | [**CustomInfo**](CustomInfo.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



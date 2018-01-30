# UpdateAccount

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | The user&#39;s account ID according to your systems. Note that user IDs are case sensitive. | [optional] [default to null]
**SessionId** | **string** | The user&#39;s current session ID, used to tie a user&#39;s action before and after login or account creation. Required if no user_id values is provided. | [optional] [default to null]
**DeviceIp** | **string** | IP address of the request made by the user. Recommended for historical backfills and customers with mobile apps. | [optional] [default to null]
**OriginTimestamp** | **string** | Represents the time the event occured in your system. Send as a UNIX timestamp in milliseconds in string. | [optional] [default to null]
**UserEmail** | **string** | Email of the user creating this order. Note - If the user&#39;s email is also their account ID in your system, set both the userId and userEmail fields to their email address. | [optional] [default to null]
**FirstName** | **string** | Provide the first name associated with the user here. | [optional] [default to null]
**LastName** | **string** | Provide the last name associated with the user here. | [optional] [default to null]
**Phone** | **string** | The primary phone number of the user associated with this account. Provide the phone number as a string. | [optional] [default to null]
**Age** | **string** | Age of the user e.g. \&quot;25\&quot; | [optional] [default to null]
**Gender** | **string** | Gender of the user e.g. \&quot;_male\&quot;, \&quot;_female\&quot; or \&quot;_trans\&quot; | [optional] [default to null]
**ReferralCode** | **string** | Code or promotion used by the user while creating account. | [optional] [default to null]
**ReferrerUserId** | **string** | The ID of the user that referred the current user to your business. This field is required for detecting referral fraud. | [optional] [default to null]
**BillingAddress** | [**BillingAddress**](BillingAddress.md) |  | [optional] [default to null]
**ShippingAddress** | [**ShippingAddress**](ShippingAddress.md) |  | [optional] [default to null]
**PaymentMethods** | [**[]PaymentMethod**](PaymentMethod.md) | The payment information associated with this account. Represented as an array of nested payment_method objects containing payment type, payment gateway, credit card bin, etc. | [optional] [default to null]
**Promotions** | [**[]Promotion**](Promotion.md) | The list of promotions that apply to this account. You can add one or more promotions when creating or updating an order. Represented as a JSON array of promotion objects. You can also separately add promotions to the account via the addPromotion event. | [optional] [default to null]
**SocialSignOnType** | **string** | If the user logged in with a social identify provider, give the name here. e.g. _google, _facebook, _twitter, _linkedin, _other | [optional] [default to null]
**EmailConfirmedStatus** | **string** | Status of email verification. e.g. _success, _failure, _pending | [optional] [default to null]
**PhoneConfirmedStatus** | **string** | Status of phone verification. e.g. _success, _failure, _pending | [optional] [default to null]
**IsNewsletterSubscribed** | **bool** | Is user subscribed for newsletter. e.g. true, false | [optional] [default to null]
**AccountStatus** | **string** | Current status of account, e.g. _active, _inactive | [optional] [default to null]
**FacebookId** | **string** | Facebook user id or token of the user. This can help to varify his social identity. | [optional] [default to null]
**GoogleId** | **string** | Google user id or token of the user. This can help to varify his social identity. | [optional] [default to null]
**TwitterId** | **string** | Twitter handle or token of the user. This can help to varify his social identity. | [optional] [default to null]
**CustomInfo** | [**CustomInfo**](CustomInfo.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



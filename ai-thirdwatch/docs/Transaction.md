# Transaction

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | The user&#39;s account ID according to your systems. Note that user IDs are case sensitive. | [optional] [default to null]
**SessionId** | **string** | The user&#39;s current session ID, used to tie a user&#39;s action before and after login or account creation. Required if no user_id values is provided. | [optional] [default to null]
**OrderId** | **string** | The ID for tracking this order in your system. | [default to null]
**TransactionId** | **string** | The ID for identifying this transaction. Important for tracking transactions, and linking different parts of the same transaction together, e.g., linking a refund to its original transaction. | [optional] [default to null]
**DeviceIp** | **string** | IP address of the request made by the user. Recommended for historical backfills and customers with mobile apps. | [optional] [default to null]
**OriginTimestamp** | **string** | Represents the time the event occured in your system. Send as a UNIX timestamp in milliseconds in string. | [optional] [default to null]
**UserEmail** | **string** | Email of the user creating this order. Note - If the user&#39;s email is also their account ID in your system, set both the userId and userEmail fields to their email address. | [optional] [default to null]
**Amount** | **string** | The item unit price in numbers, in the base unit of the currency_code.e.g. \&quot;2500\&quot; | [optional] [default to null]
**CurrencyCode** | **string** | The [ISO-4217](http://en.wikipedia.org/wiki/ISO_4217) currency code for the amount. e.g., USD, INR alternative currencies, like bitcoin or points systems. | [optional] [default to null]
**TransactionType** | **string** | The type of transaction being recorded. e.g. _sale, _authorize, _capture, _void, _refund, _deposit, _withdrawal, _transfer | [optional] [default to null]
**TransactionStatus** | **string** | Use _transactionStatus to indicate the status of the transaction. The value can be \&quot;_success\&quot; (default value), \&quot;_failure\&quot; or \&quot;_pending\&quot;. For instance, If the transaction was rejected by the payment gateway, set the value to \&quot;_failure\&quot;. | [default to null]
**IsFirstTimeBuyer** | **bool** | Is user first time buyer. | [optional] [default to null]
**BillingAddress** | [**BillingAddress**](BillingAddress.md) |  | [optional] [default to null]
**ShippingAddress** | [**ShippingAddress**](ShippingAddress.md) |  | [optional] [default to null]
**PaymentMethod** | [**PaymentMethod**](PaymentMethod.md) |  | [optional] [default to null]
**CustomInfo** | [**CustomInfo**](CustomInfo.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



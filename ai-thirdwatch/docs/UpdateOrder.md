# UpdateOrder

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | **string** | The user&#39;s account ID according to your systems. Note that user IDs are case sensitive. | [optional] [default to null]
**SessionId** | **string** | The user&#39;s current session ID, used to tie a user&#39;s action before and after login or account creation. Required if no user_id values is provided. | [optional] [default to null]
**OrderId** | **string** | The ID for tracking this order in your system. | [default to null]
**DeviceIp** | **string** | IP address of the request made by the user. Recommended for historical backfills and customers with mobile apps. | [optional] [default to null]
**OriginTimestamp** | **string** | Represents the time the event occured in your system. Send as a UNIX timestamp in milliseconds in string. | [optional] [default to null]
**UserEmail** | **string** | Email of the user creating this order. Note - If the user&#39;s email is also their account ID in your system, set both the userId and userEmail fields to their email address. | [optional] [default to null]
**Amount** | **string** | The item unit price in numbers, in the base unit of the currency_code.e.g. \&quot;2500\&quot; | [optional] [default to null]
**CurrencyCode** | **string** | The [ISO-4217](http://en.wikipedia.org/wiki/ISO_4217) currency code for the amount. e.g., USD, INR alternative currencies, like bitcoin or points systems. | [optional] [default to null]
**HasExpeditedShipping** | **bool** | Whether the user requested priority/expedited shipping on their order. | [optional] [default to null]
**ShippingMethod** | **string** | Indicates the method of delivery to the user. e.g. _electronic, _physical | [optional] [default to null]
**OrderReferrer** | **string** | Referer website or user name. | [optional] [default to null]
**IsPrePaid** | **bool** | is order is prepaid. | [optional] [default to null]
**IsGift** | **bool** | Is user chosen gift pack. | [optional] [default to null]
**IsReturn** | **bool** | Is this return order. | [optional] [default to null]
**IsFirstTimeBuyer** | **bool** | Is user first time buyer. | [optional] [default to null]
**BillingAddress** | [**BillingAddress**](BillingAddress.md) |  | [optional] [default to null]
**ShippingAddress** | [**ShippingAddress**](ShippingAddress.md) |  | [optional] [default to null]
**PaymentMethods** | [**[]PaymentMethod**](PaymentMethod.md) | The payment information associated with this order. Represented as an array of nested payment_method objects containing payment type, payment gateway, credit card bin, etc. | [optional] [default to null]
**Promotions** | [**[]Promotion**](Promotion.md) | The list of promotions that apply to this order. You can add one or more promotions when creating or updating an order. Represented as a JSON array of promotion objects. You can also separately add promotions to the account via the addPromotion event. | [optional] [default to null]
**Items** | [**[]Item**](Item.md) | The list of items ordered. Represented as a JSON array of item | [optional] [default to null]
**CustomInfo** | [**CustomInfo**](CustomInfo.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



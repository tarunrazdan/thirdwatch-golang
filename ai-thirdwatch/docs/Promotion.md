# Promotion

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PromotionId** | **string** | The ID/Coupon Code within your system that you use to represent this promotion. This ID is ideally unique to the promotion across users (e.g. \&quot;Welcome\&quot;). | [optional] [default to null]
**Status** | **string** | The status of the addition of promotion to an account. Best used with the add_promotion event. This way you can pass to Thirdwatch both successful and failed attempts when using a promotion. May be useful in spotting potential abuse. e.g. _success, _Failed | [optional] [default to null]
**Description** | **string** | Describe promotion here. | [optional] [default to null]
**Amount** | **string** | The amount or credits the promotion is worth. | [optional] [default to null]
**MinPurchaseAmount** | **string** | The minimum amount someone must spend in order for the promotion to be applied. | [optional] [default to null]
**ReferrerUserId** | **string** | The unique user ID of the user who referred the user to this promotion. | [optional] [default to null]
**FailureReason** | **string** | When adding a promotion fails, use this to describe why it failed.e.g. _alreadyUsed, _invalidCode, _notApplicable, _expired | [optional] [default to null]
**PercentageOff** | **string** | The percentage discount. If the discount is 10% off, you would send \&quot;10\&quot;. | [optional] [default to null]
**CurrencyCode** | **string** | The [ISO-4217](http://en.wikipedia.org/wiki/ISO_4217) currency code for the amount. e.g., USD, INR alternative currencies, like bitcoin or points systems. | [optional] [default to null]
**Type_** | **string** | Type of the promotion e.g., First Time, Refer, Diwali | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



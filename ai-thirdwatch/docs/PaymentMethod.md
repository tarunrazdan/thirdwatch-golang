# PaymentMethod

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PaymentType** | **string** | Values like - _cash, _check, _creditCard, _debitCard, _netBanking, _wallet, _cryptoCurrency, _electronicFundTransfer, _financing, _giftCard, _interac, _invoice, _moneyOrder, _masterPass, _points, _storeCredit, _thirdPartyProcessor, _voucher | [optional] [default to null]
**Amount** | **string** | The item unit price in numbers, in the base unit of the currency_code.e.g. \&quot;2500\&quot;. In case of multiple payment methods in order it&#39;s useful. | [optional] [default to null]
**CurrencyCode** | **string** | The [ISO-4217](http://en.wikipedia.org/wiki/ISO_4217) currency code for the amount. e.g., USD, INR alternative currencies, like bitcoin or points systems. In case of multiple payment methods in order it&#39;s useful. | [optional] [default to null]
**PaymentGateway** | **string** | fill value like bank name, gateway name, wallet name etc, e.g. payu, paypal, icici, paytm | [optional] [default to null]
**AccountName** | **string** | Account name oif the user for that payment method | [optional] [default to null]
**CardBin** | **string** | The first six digits of the credit card number. These numbers contain information about the card issuer, the geography and other card details. | [optional] [default to null]
**AvsResponseCode** | **string** | Response code from the AVS address verification system. Used in payments involving credit cards. | [optional] [default to null]
**CvvResponseCode** | **string** | Response code from the credit card company indicating if the CVV number entered matches the number on record. Used in payments involving credit cards. | [optional] [default to null]
**CardLast4** | **string** | The last four digits of the credit card number. | [optional] [default to null]
**CardExpiryMonth** | **string** | Expiry month of the card. | [optional] [default to null]
**CardExpiryYear** | **string** | Expiry year of the card. | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# \TransactionApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Transaction**](TransactionApi.md#Transaction) | **Post** /v1/transaction | Use transaction to record attempts results to Pay, Transfer money, Refund or other transactions.


# **Transaction**
> EventResponse Transaction($jSON)

Use transaction to record attempts results to Pay, Transfer money, Refund or other transactions.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**Transaction**](Transaction.md)| Pass transaction results to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain transaction info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \ChargebackApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Chargeback**](ChargebackApi.md#Chargeback) | **Post** /v1/chargeback | Use chargeback to capture a chargeback reported on a transaction. This event can be called multiple times to record changes to the chargeback state.


# **Chargeback**
> EventResponse Chargeback($jSON)

Use chargeback to capture a chargeback reported on a transaction. This event can be called multiple times to record changes to the chargeback state.

Note - When you send a chargeback event you also need to send a label event if you want to prevent the user from making another purchase. 


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**Chargeback**](Chargeback.md)| Pass chargeback to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain chargeback info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


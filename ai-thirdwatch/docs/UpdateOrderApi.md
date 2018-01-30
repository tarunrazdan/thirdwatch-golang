# \UpdateOrderApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**UpdateOrder**](UpdateOrderApi.md#UpdateOrder) | **Post** /v1/update_order | Update details of an existing order.


# **UpdateOrder**
> EventResponse UpdateOrder($jSON)

Update details of an existing order.

* This event contains the same fields as ```create_order```. * The existing order will be completely replaced by the values sent in `update_order`. Be sure to specify all values for the order, not just those that changed. * If no matching `_orderId` found, a new order will be created. 


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**UpdateOrder**](UpdateOrder.md)| Update details of an existing order. Only &#x60;_userID&#x60; is required field. But this should contain existing order info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


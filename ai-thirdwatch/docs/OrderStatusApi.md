# \OrderStatusApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OrderStatus**](OrderStatusApi.md#OrderStatus) | **Post** /v1/order_status | Use order_status to track the order processing workflow of a previously submitted order.


# **OrderStatus**
> EventResponse OrderStatus($jSON)

Use order_status to track the order processing workflow of a previously submitted order.

For example, order_status can be used to indicate that an order has been held for review, canceled due to suspected fraud, or fulfilled. This event can be called multiple times to record changes an order's status. 


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**OrderStatus**](OrderStatus.md)| Pass order status to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain order info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


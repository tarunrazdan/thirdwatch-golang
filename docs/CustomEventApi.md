# \CustomEventApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CustomEvent**](CustomEventApi.md#CustomEvent) | **Post** /v1/custom_event | Use order_status to track the order processing workflow of a previously submitted order.


# **CustomEvent**
> EventResponse CustomEvent($jSON)

Use order_status to track the order processing workflow of a previously submitted order.

Custom events and fields capture user behavior and differences not covered by our reserved events and fields. For example, a location tracking business can create a custom event called trackLocation with custom fields that are relevant. 


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**Custom**](Custom.md)| Pass order status to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain custom info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


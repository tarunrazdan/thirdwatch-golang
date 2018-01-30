# \SendMessageApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SendMessage**](SendMessageApi.md#SendMessage) | **Post** /v1/send_message | Use send_message to record when a user sends a message to other i.e. seller, support.


# **SendMessage**
> EventResponse SendMessage($jSON)

Use send_message to record when a user sends a message to other i.e. seller, support.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**SendMessage**](SendMessage.md)| Pass message to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain message info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


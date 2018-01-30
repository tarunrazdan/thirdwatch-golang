# \ItemStatusApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ItemStatus**](ItemStatusApi.md#ItemStatus) | **Post** /v1/item_status | Use item_status to update the status of item that you’ve already pass to Thirdwatch.


# **ItemStatus**
> EventResponse ItemStatus($jSON)

Use item_status to update the status of item that you’ve already pass to Thirdwatch.

If the status is the only thing that’s changing about the item, use this as a convenient way to send status of the item after order processing. 


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**ItemStatus**](ItemStatus.md)| Pass change item status to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain item status. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


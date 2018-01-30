# \LogoutApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Logout**](LogoutApi.md#Logout) | **Post** /v1/logout | Use logout to record when a user logs out.


# **Logout**
> EventResponse Logout($jSON)

Use logout to record when a user logs out.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**Logout**](Logout.md)| Pass logout status to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain logout info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \LoginApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Login**](LoginApi.md#Login) | **Post** /v1/login | Use login to record when a user attempts to log in.


# **Login**
> EventResponse Login($jSON)

Use login to record when a user attempts to log in.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**Login**](Login.md)| Pass login status to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain login info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


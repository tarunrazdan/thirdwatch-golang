# \UpdateAccountApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**UpdateAccount**](UpdateAccountApi.md#UpdateAccount) | **Post** /v1/update_account | Use update_account to record changes to the user&#39;s account information.


# **UpdateAccount**
> EventResponse UpdateAccount($jSON)

Use update_account to record changes to the user's account information.

For user accounts created before integration with Thirdwatch, there's no need to call `create_account` before `update_account`. Simply call `update_account` and we'll infer that account was created before integration. 


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**UpdateAccount**](UpdateAccount.md)| Pass user details after update or change in user info. Only &#x60;_userID&#x60; is required field. But this should contain user info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


# \CreateAccountApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAccount**](CreateAccountApi.md#CreateAccount) | **Post** /v1/create_account | Use create_account to pass user details at user registration.


# **CreateAccount**
> EventResponse CreateAccount($jSON)

Use create_account to pass user details at user registration.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**CreateAccount**](CreateAccount.md)| Pass user details after registration. Only &#x60;_userID&#x60; is required field. But this should contain user info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


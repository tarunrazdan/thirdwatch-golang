# \LinkSessionToUserApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**LinkSessionToUser**](LinkSessionToUserApi.md#LinkSessionToUser) | **Post** /v1/link_session_to_user | Use link_session_to_user to associate specific session to a user. Generally used only in anonymous checkout workflows.


# **LinkSessionToUser**
> EventResponse LinkSessionToUser($jSON)

Use link_session_to_user to associate specific session to a user. Generally used only in anonymous checkout workflows.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**LinkSessionToUser**](LinkSessionToUser.md)| Pass session and user to thirdwatch for link. Only &#x60;_userID&#x60; is required field. But this should contain session and user info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


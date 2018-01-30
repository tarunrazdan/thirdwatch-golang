# \RemoveFromCartApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RemoveFromCart**](RemoveFromCartApi.md#RemoveFromCart) | **Post** /v1/remove_from_cart | Use remove_from_cart when a user removes an item from their shopping cart or list.


# **RemoveFromCart**
> EventResponse RemoveFromCart($jSON)

Use remove_from_cart when a user removes an item from their shopping cart or list.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**RemoveFromCart**](RemoveFromCart.md)| Pass removed item info to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain item info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


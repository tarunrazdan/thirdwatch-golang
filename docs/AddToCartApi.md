# \AddToCartApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddToCart**](AddToCartApi.md#AddToCart) | **Post** /v1/add_to_cart | Use add_to_cart when a user adds an item to their shopping cart or list.


# **AddToCart**
> EventResponse AddToCart($jSON)

Use add_to_cart when a user adds an item to their shopping cart or list.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**AddToCart**](AddToCart.md)| Pass added item info to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain item info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


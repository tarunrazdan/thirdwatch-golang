# \UntagAPIApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**UnTagUser**](UntagAPIApi.md#UnTagUser) | **Post** /v1/untag | If you are unsure whether a user is bad or good, you can always remove tag and leave the user in a neutral state.


# **UnTagUser**
> EventResponse UnTagUser($jSON)

If you are unsure whether a user is bad or good, you can always remove tag and leave the user in a neutral state.

To untag a user for a particular abuse type, send the abuse_type key in json data. In the rare case that you want to remove all tags for all abuse types for a particular user, send without the abuse_type query parameter. 


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**UnTag**](UnTag.md)| Pass user and it&#39;s info to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain untag info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


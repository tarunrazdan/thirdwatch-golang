# \AddPromotionApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddPromotion**](AddPromotionApi.md#AddPromotion) | **Post** /v1/add_promotion | Use add_promotion to record when a user adds one or more promotions to their account.


# **AddPromotion**
> EventResponse AddPromotion($jSON)

Use add_promotion to record when a user adds one or more promotions to their account.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**AddPromotion**](AddPromotion.md)| Pass added promotion info to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain promotion info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


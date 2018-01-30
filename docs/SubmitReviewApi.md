# \SubmitReviewApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SubmitReview**](SubmitReviewApi.md#SubmitReview) | **Post** /v1/submit_review | Use submit_review when a user-submitted review of a product or seller.


# **SubmitReview**
> EventResponse SubmitReview($jSON)

Use submit_review when a user-submitted review of a product or seller.


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**SubmitReview**](SubmitReview.md)| Pass review to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain review info. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


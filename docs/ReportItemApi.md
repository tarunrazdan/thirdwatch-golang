# \ReportItemApi

All URIs are relative to *https://localhost/event*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ReportItem**](ReportItemApi.md#ReportItem) | **Post** /v1/report_item | Use report_item to let us know when another user reports that this item may violate your company’s policies.


# **ReportItem**
> EventResponse ReportItem($jSON)

Use report_item to let us know when another user reports that this item may violate your company’s policies.

If you have a feature like \"Report Item\" or \"Flag this Item\", send that event to us using this. 


### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jSON** | [**ReportItem**](ReportItem.md)| Pass report item info to thirdwatch. Only &#x60;_userID&#x60; is required field. But this should contain item id. | 

### Return type

[**EventResponse**](EventResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


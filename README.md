# Go API client for ai-thirdwatch

The first version of the Thirdwatch API is an exciting step forward towards making it easier for developers to pass data to Thirdwatch.

# Introduction
Once you've [registered your website/app](https://www.thirdwatch.ai/) it's easy to start sending data to Thirdwatch.

All endpoints are only accessible via https and are located at
`api.thirdwatch.ai` . For instance: you can send event at the moment
by ```HTTPS POST``` request to the following URL with your API key in
```Header``` and ```JSON``` data in request body.

```   https://api.thirdwatch.ai/event/v1 ``` 

Every API request must contain ```API Key``` in header value ```X-THIRDWATCH-API-KEY```. Every event must contain your ```_userId``` (if this is not available, you can alternatively provide a ```_sessionId``` value also in ```_userId```). 

- API version: 0.0.1

## Installation
Put the package under your project folder and add the following in import:
```
    "./ai_thirdwatch"
```

## Documentation for API Endpoints

All URIs are relative to *https://localhost/event*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AddPromotionApi* | [**AddPromotion**](docs/AddPromotionApi.md#addpromotion) | **Post** /v1/add_promotion | Use add_promotion to record when a user adds one or more promotions to their account.
*AddToCartApi* | [**AddToCart**](docs/AddToCartApi.md#addtocart) | **Post** /v1/add_to_cart | Use add_to_cart when a user adds an item to their shopping cart or list.
*ChargebackApi* | [**Chargeback**](docs/ChargebackApi.md#chargeback) | **Post** /v1/chargeback | Use chargeback to capture a chargeback reported on a transaction. This event can be called multiple times to record changes to the chargeback state.
*CreateAccountApi* | [**CreateAccount**](docs/CreateAccountApi.md#createaccount) | **Post** /v1/create_account | Use create_account to pass user details at user registration.
*CreateOrderApi* | [**CreateOrder**](docs/CreateOrderApi.md#createorder) | **Post** /v1/createOrder | Submit a new or existing order to Thirdwatch for review. This API should contain order item info, the payment info, and user identity info.
*CustomEventApi* | [**CustomEvent**](docs/CustomEventApi.md#customevent) | **Post** /v1/custom_event | Use order_status to track the order processing workflow of a previously submitted order.
*ItemStatusApi* | [**ItemStatus**](docs/ItemStatusApi.md#itemstatus) | **Post** /v1/item_status | Use item_status to update the status of item that you’ve already pass to Thirdwatch.
*LinkSessionToUserApi* | [**LinkSessionToUser**](docs/LinkSessionToUserApi.md#linksessiontouser) | **Post** /v1/link_session_to_user | Use link_session_to_user to associate specific session to a user. Generally used only in anonymous checkout workflows.
*LoginApi* | [**Login**](docs/LoginApi.md#login) | **Post** /v1/login | Use login to record when a user attempts to log in.
*LogoutApi* | [**Logout**](docs/LogoutApi.md#logout) | **Post** /v1/logout | Use logout to record when a user logs out.
*OrderStatusApi* | [**OrderStatus**](docs/OrderStatusApi.md#orderstatus) | **Post** /v1/order_status | Use order_status to track the order processing workflow of a previously submitted order.
*RemoveFromCartApi* | [**RemoveFromCart**](docs/RemoveFromCartApi.md#removefromcart) | **Post** /v1/remove_from_cart | Use remove_from_cart when a user removes an item from their shopping cart or list.
*ReportItemApi* | [**ReportItem**](docs/ReportItemApi.md#reportitem) | **Post** /v1/report_item | Use report_item to let us know when another user reports that this item may violate your company’s policies.
*SendMessageApi* | [**SendMessage**](docs/SendMessageApi.md#sendmessage) | **Post** /v1/send_message | Use send_message to record when a user sends a message to other i.e. seller, support.
*SubmitReviewApi* | [**SubmitReview**](docs/SubmitReviewApi.md#submitreview) | **Post** /v1/submit_review | Use submit_review when a user-submitted review of a product or seller.
*TagAPIApi* | [**TagUser**](docs/TagAPIApi.md#taguser) | **Post** /v1/tag | The Tag API enables you to tell Thirdwatch which of your users are bad and which are good.
*TransactionApi* | [**Transaction**](docs/TransactionApi.md#transaction) | **Post** /v1/transaction | Use transaction to record attempts results to Pay, Transfer money, Refund or other transactions.
*UntagAPIApi* | [**UnTagUser**](docs/UntagAPIApi.md#untaguser) | **Post** /v1/untag | If you are unsure whether a user is bad or good, you can always remove tag and leave the user in a neutral state.
*UpdateAccountApi* | [**UpdateAccount**](docs/UpdateAccountApi.md#updateaccount) | **Post** /v1/update_account | Use update_account to record changes to the user&#39;s account information.
*UpdateOrderApi* | [**UpdateOrder**](docs/UpdateOrderApi.md#updateorder) | **Post** /v1/update_order | Update details of an existing order.


## Documentation For Models

 - [AddPromotion](docs/AddPromotion.md)
 - [AddToCart](docs/AddToCart.md)
 - [BillingAddress](docs/BillingAddress.md)
 - [Chargeback](docs/Chargeback.md)
 - [CreateAccount](docs/CreateAccount.md)
 - [CreateOrder](docs/CreateOrder.md)
 - [Custom](docs/Custom.md)
 - [CustomInfo](docs/CustomInfo.md)
 - [ErrorResponse](docs/ErrorResponse.md)
 - [EventResponse](docs/EventResponse.md)
 - [Item](docs/Item.md)
 - [ItemStatus](docs/ItemStatus.md)
 - [LinkSessionToUser](docs/LinkSessionToUser.md)
 - [Login](docs/Login.md)
 - [Logout](docs/Logout.md)
 - [OrderStatus](docs/OrderStatus.md)
 - [PaymentMethod](docs/PaymentMethod.md)
 - [Promotion](docs/Promotion.md)
 - [RemoveFromCart](docs/RemoveFromCart.md)
 - [ReportItem](docs/ReportItem.md)
 - [Seller](docs/Seller.md)
 - [SendMessage](docs/SendMessage.md)
 - [ShippingAddress](docs/ShippingAddress.md)
 - [SubmitReview](docs/SubmitReview.md)
 - [Tag](docs/Tag.md)
 - [Transaction](docs/Transaction.md)
 - [UnTag](docs/UnTag.md)
 - [UpdateAccount](docs/UpdateAccount.md)
 - [UpdateOrder](docs/UpdateOrder.md)


## Documentation For Authorization


## api_key

- **Type**: API key 
- **API key parameter name**: X-THIRDWATCH-API-KEY
- **Location**: HTTP header


## Author



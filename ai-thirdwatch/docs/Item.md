# Item

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ItemId** | **string** | The item&#39;s unique identifier according to your systems. Use the same ID that you would use to look up items on your website&#39;s database. | [optional] [default to null]
**ProductTitle** | **string** | The item&#39;s name, e.g., \&quot;WD 2 TB External Hard Drive\&quot;. | [optional] [default to null]
**Price** | **string** | The item unit price in numbers, in the base unit of the currency_code.e.g. \&quot;2500\&quot; | [optional] [default to null]
**CurrencyCode** | **string** | The [ISO-4217](http://en.wikipedia.org/wiki/ISO_4217) currency code for the amount. e.g., USD, INR alternative currencies, like bitcoin or points systems. | [optional] [default to null]
**Upc** | **string** | If the item has a Universal Product Code (UPC), provide it here. | [optional] [default to null]
**Sku** | **string** | If the item has a Stock-keeping Unit ID (SKU), provide it here. | [optional] [default to null]
**Isbn** | **string** | If the item is a book with an International Standard Book Number (ISBN), provide it here. | [optional] [default to null]
**Brand** | **string** | The brand name of the item. | [optional] [default to null]
**Manufacturer** | **string** | Name of the item&#39;s manufacturer. | [optional] [default to null]
**Category** | **string** | The category this item is listed under in your business. e.g., \&quot;travel\&quot;, \&quot;man &gt; bags\&quot;. | [optional] [default to null]
**Tags** | **string** | The tags used to describe this item in your business. e.g., \&quot;man\&quot;, \&quot;summer\&quot;. | [optional] [default to null]
**Color** | **string** | The color of the item. | [optional] [default to null]
**Quantity** | **int64** | The quantity of the item. | [optional] [default to null]
**IsOnSale** | **bool** | Is item on sale or running offers on this item . | [optional] [default to null]
**MaxQuantity** | **int64** | The max quantity per user for this item. | [optional] [default to null]
**DiscountPrice** | **string** | Price of the product after discount. | [optional] [default to null]
**ProductWeight** | **string** | Weight of the product in Kilo Gram, e.g. \&quot;3\&quot; , \&quot;0.5\&quot; | [optional] [default to null]
**Country** | **string** | The [ISO-3166](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) country code of the item, e.g., \&quot;IN\&quot; in case of India. | [optional] [default to null]
**DescriptionShort** | **string** | Short description of the item. | [optional] [default to null]
**Description** | **string** | Detail description of the item. | [optional] [default to null]
**Seller** | [**Seller**](Seller.md) |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



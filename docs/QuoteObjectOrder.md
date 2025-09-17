# QuoteObjectOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quote** | **int32** |  | 
**Price** | [**PriceDetails**](PriceDetails.md) |  | 
**Currency** | **string** |  | 

## Methods

### NewQuoteObjectOrder

`func NewQuoteObjectOrder(quote int32, price PriceDetails, currency string, ) *QuoteObjectOrder`

NewQuoteObjectOrder instantiates a new QuoteObjectOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuoteObjectOrderWithDefaults

`func NewQuoteObjectOrderWithDefaults() *QuoteObjectOrder`

NewQuoteObjectOrderWithDefaults instantiates a new QuoteObjectOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuote

`func (o *QuoteObjectOrder) GetQuote() int32`

GetQuote returns the Quote field if non-nil, zero value otherwise.

### GetQuoteOk

`func (o *QuoteObjectOrder) GetQuoteOk() (*int32, bool)`

GetQuoteOk returns a tuple with the Quote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuote

`func (o *QuoteObjectOrder) SetQuote(v int32)`

SetQuote sets Quote field to given value.


### GetPrice

`func (o *QuoteObjectOrder) GetPrice() PriceDetails`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *QuoteObjectOrder) GetPriceOk() (*PriceDetails, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *QuoteObjectOrder) SetPrice(v PriceDetails)`

SetPrice sets Price field to given value.


### GetCurrency

`func (o *QuoteObjectOrder) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *QuoteObjectOrder) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *QuoteObjectOrder) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



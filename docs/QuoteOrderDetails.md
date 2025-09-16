# QuoteOrderDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quote** | **int32** |  | 
**Price** | [**PriceDetails**](PriceDetails.md) |  | 
**Currency** | **string** |  | 
**MethodNo** | **int32** |  | 
**MethodName** | **string** |  | 

## Methods

### NewQuoteOrderDetails

`func NewQuoteOrderDetails(quote int32, price PriceDetails, currency string, methodNo int32, methodName string, ) *QuoteOrderDetails`

NewQuoteOrderDetails instantiates a new QuoteOrderDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuoteOrderDetailsWithDefaults

`func NewQuoteOrderDetailsWithDefaults() *QuoteOrderDetails`

NewQuoteOrderDetailsWithDefaults instantiates a new QuoteOrderDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuote

`func (o *QuoteOrderDetails) GetQuote() int32`

GetQuote returns the Quote field if non-nil, zero value otherwise.

### GetQuoteOk

`func (o *QuoteOrderDetails) GetQuoteOk() (*int32, bool)`

GetQuoteOk returns a tuple with the Quote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuote

`func (o *QuoteOrderDetails) SetQuote(v int32)`

SetQuote sets Quote field to given value.


### GetPrice

`func (o *QuoteOrderDetails) GetPrice() PriceDetails`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *QuoteOrderDetails) GetPriceOk() (*PriceDetails, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *QuoteOrderDetails) SetPrice(v PriceDetails)`

SetPrice sets Price field to given value.


### GetCurrency

`func (o *QuoteOrderDetails) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *QuoteOrderDetails) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *QuoteOrderDetails) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetMethodNo

`func (o *QuoteOrderDetails) GetMethodNo() int32`

GetMethodNo returns the MethodNo field if non-nil, zero value otherwise.

### GetMethodNoOk

`func (o *QuoteOrderDetails) GetMethodNoOk() (*int32, bool)`

GetMethodNoOk returns a tuple with the MethodNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethodNo

`func (o *QuoteOrderDetails) SetMethodNo(v int32)`

SetMethodNo sets MethodNo field to given value.


### GetMethodName

`func (o *QuoteOrderDetails) GetMethodName() string`

GetMethodName returns the MethodName field if non-nil, zero value otherwise.

### GetMethodNameOk

`func (o *QuoteOrderDetails) GetMethodNameOk() (*string, bool)`

GetMethodNameOk returns a tuple with the MethodName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethodName

`func (o *QuoteOrderDetails) SetMethodName(v string)`

SetMethodName sets MethodName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



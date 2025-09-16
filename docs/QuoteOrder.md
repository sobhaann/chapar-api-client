# QuoteOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Quote** | Pointer to **int32** |  | [optional] 
**Price** | Pointer to [**Price**](Price.md) |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 

## Methods

### NewQuoteOrder

`func NewQuoteOrder() *QuoteOrder`

NewQuoteOrder instantiates a new QuoteOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuoteOrderWithDefaults

`func NewQuoteOrderWithDefaults() *QuoteOrder`

NewQuoteOrderWithDefaults instantiates a new QuoteOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuote

`func (o *QuoteOrder) GetQuote() int32`

GetQuote returns the Quote field if non-nil, zero value otherwise.

### GetQuoteOk

`func (o *QuoteOrder) GetQuoteOk() (*int32, bool)`

GetQuoteOk returns a tuple with the Quote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuote

`func (o *QuoteOrder) SetQuote(v int32)`

SetQuote sets Quote field to given value.

### HasQuote

`func (o *QuoteOrder) HasQuote() bool`

HasQuote returns a boolean if a field has been set.

### GetPrice

`func (o *QuoteOrder) GetPrice() Price`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *QuoteOrder) GetPriceOk() (*Price, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *QuoteOrder) SetPrice(v Price)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *QuoteOrder) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *QuoteOrder) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *QuoteOrder) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *QuoteOrder) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *QuoteOrder) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# QuoteData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Price** | Pointer to **int32** |  | [optional] 
**Deadline** | Pointer to **string** |  | [optional] 

## Methods

### NewQuoteData

`func NewQuoteData() *QuoteData`

NewQuoteData instantiates a new QuoteData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuoteDataWithDefaults

`func NewQuoteDataWithDefaults() *QuoteData`

NewQuoteDataWithDefaults instantiates a new QuoteData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrice

`func (o *QuoteData) GetPrice() int32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *QuoteData) GetPriceOk() (*int32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *QuoteData) SetPrice(v int32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *QuoteData) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetDeadline

`func (o *QuoteData) GetDeadline() string`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *QuoteData) GetDeadlineOk() (*string, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *QuoteData) SetDeadline(v string)`

SetDeadline sets Deadline field to given value.

### HasDeadline

`func (o *QuoteData) HasDeadline() bool`

HasDeadline returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



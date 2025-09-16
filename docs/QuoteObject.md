# QuoteObject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Price** | Pointer to **int32** |  | [optional] 
**Deadline** | Pointer to **string** |  | [optional] 

## Methods

### NewQuoteObject

`func NewQuoteObject() *QuoteObject`

NewQuoteObject instantiates a new QuoteObject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuoteObjectWithDefaults

`func NewQuoteObjectWithDefaults() *QuoteObject`

NewQuoteObjectWithDefaults instantiates a new QuoteObject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrice

`func (o *QuoteObject) GetPrice() int32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *QuoteObject) GetPriceOk() (*int32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *QuoteObject) SetPrice(v int32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *QuoteObject) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetDeadline

`func (o *QuoteObject) GetDeadline() string`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *QuoteObject) GetDeadlineOk() (*string, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *QuoteObject) SetDeadline(v string)`

SetDeadline sets Deadline field to given value.

### HasDeadline

`func (o *QuoteObject) HasDeadline() bool`

HasDeadline returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



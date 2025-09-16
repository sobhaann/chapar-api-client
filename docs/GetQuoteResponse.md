# GetQuoteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to [**QuoteOrder**](QuoteOrder.md) |  | [optional] 

## Methods

### NewGetQuoteResponse

`func NewGetQuoteResponse() *GetQuoteResponse`

NewGetQuoteResponse instantiates a new GetQuoteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetQuoteResponseWithDefaults

`func NewGetQuoteResponseWithDefaults() *GetQuoteResponse`

NewGetQuoteResponseWithDefaults instantiates a new GetQuoteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *GetQuoteResponse) GetOrder() QuoteOrder`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *GetQuoteResponse) GetOrderOk() (*QuoteOrder, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *GetQuoteResponse) SetOrder(v QuoteOrder)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *GetQuoteResponse) HasOrder() bool`

HasOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



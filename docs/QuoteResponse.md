# QuoteResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**Object** | Pointer to [**QuoteObject**](QuoteObject.md) |  | [optional] 

## Methods

### NewQuoteResponse

`func NewQuoteResponse() *QuoteResponse`

NewQuoteResponse instantiates a new QuoteResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQuoteResponseWithDefaults

`func NewQuoteResponseWithDefaults() *QuoteResponse`

NewQuoteResponseWithDefaults instantiates a new QuoteResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *QuoteResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *QuoteResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *QuoteResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *QuoteResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetMessage

`func (o *QuoteResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *QuoteResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *QuoteResponse) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *QuoteResponse) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *QuoteResponse) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *QuoteResponse) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetObject

`func (o *QuoteResponse) GetObject() QuoteObject`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *QuoteResponse) GetObjectOk() (*QuoteObject, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *QuoteResponse) SetObject(v QuoteObject)`

SetObject sets Object field to given value.

### HasObject

`func (o *QuoteResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



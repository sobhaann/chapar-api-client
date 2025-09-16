# GetStateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**Object** | Pointer to [**GetStateObject**](GetStateObject.md) |  | [optional] 

## Methods

### NewGetStateResponse

`func NewGetStateResponse() *GetStateResponse`

NewGetStateResponse instantiates a new GetStateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetStateResponseWithDefaults

`func NewGetStateResponseWithDefaults() *GetStateResponse`

NewGetStateResponseWithDefaults instantiates a new GetStateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetStateResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetStateResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetStateResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *GetStateResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetMessage

`func (o *GetStateResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *GetStateResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *GetStateResponse) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *GetStateResponse) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *GetStateResponse) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *GetStateResponse) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetObject

`func (o *GetStateResponse) GetObject() GetStateObject`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *GetStateResponse) GetObjectOk() (*GetStateObject, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *GetStateResponse) SetObject(v GetStateObject)`

SetObject sets Object field to given value.

### HasObject

`func (o *GetStateResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



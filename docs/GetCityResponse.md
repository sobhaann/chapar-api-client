# GetCityResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**Object** | Pointer to [**GetCityObject**](GetCityObject.md) |  | [optional] 

## Methods

### NewGetCityResponse

`func NewGetCityResponse() *GetCityResponse`

NewGetCityResponse instantiates a new GetCityResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCityResponseWithDefaults

`func NewGetCityResponseWithDefaults() *GetCityResponse`

NewGetCityResponseWithDefaults instantiates a new GetCityResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetCityResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetCityResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetCityResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *GetCityResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetMessage

`func (o *GetCityResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *GetCityResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *GetCityResponse) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *GetCityResponse) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *GetCityResponse) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *GetCityResponse) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetObject

`func (o *GetCityResponse) GetObject() GetCityObject`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *GetCityResponse) GetObjectOk() (*GetCityObject, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *GetCityResponse) SetObject(v GetCityObject)`

SetObject sets Object field to given value.

### HasObject

`func (o *GetCityResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetCityResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | **bool** |  | 
**Message** | Pointer to **NullableString** |  | [optional] 
**Object** | [**GetCityObject**](GetCityObject.md) |  | 

## Methods

### NewGetCityResponse

`func NewGetCityResponse(result bool, object GetCityObject, ) *GetCityResponse`

NewGetCityResponse instantiates a new GetCityResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCityResponseWithDefaults

`func NewGetCityResponseWithDefaults() *GetCityResponse`

NewGetCityResponseWithDefaults instantiates a new GetCityResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *GetCityResponse) GetResult() bool`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *GetCityResponse) GetResultOk() (*bool, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *GetCityResponse) SetResult(v bool)`

SetResult sets Result field to given value.


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



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



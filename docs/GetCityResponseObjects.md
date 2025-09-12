# GetCityResponseObjects

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**City** | Pointer to [**[]City**](City.md) |  | [optional] 
**Selected** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewGetCityResponseObjects

`func NewGetCityResponseObjects() *GetCityResponseObjects`

NewGetCityResponseObjects instantiates a new GetCityResponseObjects object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCityResponseObjectsWithDefaults

`func NewGetCityResponseObjectsWithDefaults() *GetCityResponseObjects`

NewGetCityResponseObjectsWithDefaults instantiates a new GetCityResponseObjects object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCity

`func (o *GetCityResponseObjects) GetCity() []City`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *GetCityResponseObjects) GetCityOk() (*[]City, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *GetCityResponseObjects) SetCity(v []City)`

SetCity sets City field to given value.

### HasCity

`func (o *GetCityResponseObjects) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetSelected

`func (o *GetCityResponseObjects) GetSelected() map[string]interface{}`

GetSelected returns the Selected field if non-nil, zero value otherwise.

### GetSelectedOk

`func (o *GetCityResponseObjects) GetSelectedOk() (*map[string]interface{}, bool)`

GetSelectedOk returns a tuple with the Selected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelected

`func (o *GetCityResponseObjects) SetSelected(v map[string]interface{})`

SetSelected sets Selected field to given value.

### HasSelected

`func (o *GetCityResponseObjects) HasSelected() bool`

HasSelected returns a boolean if a field has been set.

### SetSelectedNil

`func (o *GetCityResponseObjects) SetSelectedNil(b bool)`

 SetSelectedNil sets the value for Selected to be an explicit nil

### UnsetSelected
`func (o *GetCityResponseObjects) UnsetSelected()`

UnsetSelected ensures that no value is present for Selected, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



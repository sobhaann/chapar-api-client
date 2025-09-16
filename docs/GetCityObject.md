# GetCityObject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**City** | [**[]City**](City.md) |  | 
**Selected** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewGetCityObject

`func NewGetCityObject(city []City, ) *GetCityObject`

NewGetCityObject instantiates a new GetCityObject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCityObjectWithDefaults

`func NewGetCityObjectWithDefaults() *GetCityObject`

NewGetCityObjectWithDefaults instantiates a new GetCityObject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCity

`func (o *GetCityObject) GetCity() []City`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *GetCityObject) GetCityOk() (*[]City, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *GetCityObject) SetCity(v []City)`

SetCity sets City field to given value.


### GetSelected

`func (o *GetCityObject) GetSelected() map[string]interface{}`

GetSelected returns the Selected field if non-nil, zero value otherwise.

### GetSelectedOk

`func (o *GetCityObject) GetSelectedOk() (*map[string]interface{}, bool)`

GetSelectedOk returns a tuple with the Selected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelected

`func (o *GetCityObject) SetSelected(v map[string]interface{})`

SetSelected sets Selected field to given value.

### HasSelected

`func (o *GetCityObject) HasSelected() bool`

HasSelected returns a boolean if a field has been set.

### SetSelectedNil

`func (o *GetCityObject) SetSelectedNil(b bool)`

 SetSelectedNil sets the value for Selected to be an explicit nil

### UnsetSelected
`func (o *GetCityObject) UnsetSelected()`

UnsetSelected ensures that no value is present for Selected, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



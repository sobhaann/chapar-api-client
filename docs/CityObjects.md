# CityObjects

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**City** | Pointer to [**[]City**](City.md) |  | [optional] 
**Selected** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewCityObjects

`func NewCityObjects() *CityObjects`

NewCityObjects instantiates a new CityObjects object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCityObjectsWithDefaults

`func NewCityObjectsWithDefaults() *CityObjects`

NewCityObjectsWithDefaults instantiates a new CityObjects object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCity

`func (o *CityObjects) GetCity() []City`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *CityObjects) GetCityOk() (*[]City, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *CityObjects) SetCity(v []City)`

SetCity sets City field to given value.

### HasCity

`func (o *CityObjects) HasCity() bool`

HasCity returns a boolean if a field has been set.

### GetSelected

`func (o *CityObjects) GetSelected() map[string]interface{}`

GetSelected returns the Selected field if non-nil, zero value otherwise.

### GetSelectedOk

`func (o *CityObjects) GetSelectedOk() (*map[string]interface{}, bool)`

GetSelectedOk returns a tuple with the Selected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelected

`func (o *CityObjects) SetSelected(v map[string]interface{})`

SetSelected sets Selected field to given value.

### HasSelected

`func (o *CityObjects) HasSelected() bool`

HasSelected returns a boolean if a field has been set.

### SetSelectedNil

`func (o *CityObjects) SetSelectedNil(b bool)`

 SetSelectedNil sets the value for Selected to be an explicit nil

### UnsetSelected
`func (o *CityObjects) UnsetSelected()`

UnsetSelected ensures that no value is present for Selected, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



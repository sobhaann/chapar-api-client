# GetCityObjectObjects

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**City** | [**[]CityItem**](CityItem.md) |  | 
**Selected** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewGetCityObjectObjects

`func NewGetCityObjectObjects(city []CityItem, ) *GetCityObjectObjects`

NewGetCityObjectObjects instantiates a new GetCityObjectObjects object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCityObjectObjectsWithDefaults

`func NewGetCityObjectObjectsWithDefaults() *GetCityObjectObjects`

NewGetCityObjectObjectsWithDefaults instantiates a new GetCityObjectObjects object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCity

`func (o *GetCityObjectObjects) GetCity() []CityItem`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *GetCityObjectObjects) GetCityOk() (*[]CityItem, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *GetCityObjectObjects) SetCity(v []CityItem)`

SetCity sets City field to given value.


### GetSelected

`func (o *GetCityObjectObjects) GetSelected() map[string]interface{}`

GetSelected returns the Selected field if non-nil, zero value otherwise.

### GetSelectedOk

`func (o *GetCityObjectObjects) GetSelectedOk() (*map[string]interface{}, bool)`

GetSelectedOk returns a tuple with the Selected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelected

`func (o *GetCityObjectObjects) SetSelected(v map[string]interface{})`

SetSelected sets Selected field to given value.

### HasSelected

`func (o *GetCityObjectObjects) HasSelected() bool`

HasSelected returns a boolean if a field has been set.

### SetSelectedNil

`func (o *GetCityObjectObjects) SetSelectedNil(b bool)`

 SetSelectedNil sets the value for Selected to be an explicit nil

### UnsetSelected
`func (o *GetCityObjectObjects) UnsetSelected()`

UnsetSelected ensures that no value is present for Selected, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



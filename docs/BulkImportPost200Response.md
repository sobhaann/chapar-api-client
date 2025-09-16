# BulkImportPost200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | **bool** |  | 
**Message** | Pointer to **NullableString** |  | [optional] 
**Objects** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewBulkImportPost200Response

`func NewBulkImportPost200Response(result bool, ) *BulkImportPost200Response`

NewBulkImportPost200Response instantiates a new BulkImportPost200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkImportPost200ResponseWithDefaults

`func NewBulkImportPost200ResponseWithDefaults() *BulkImportPost200Response`

NewBulkImportPost200ResponseWithDefaults instantiates a new BulkImportPost200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *BulkImportPost200Response) GetResult() bool`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *BulkImportPost200Response) GetResultOk() (*bool, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *BulkImportPost200Response) SetResult(v bool)`

SetResult sets Result field to given value.


### GetMessage

`func (o *BulkImportPost200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *BulkImportPost200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *BulkImportPost200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *BulkImportPost200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *BulkImportPost200Response) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *BulkImportPost200Response) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetObjects

`func (o *BulkImportPost200Response) GetObjects() map[string]interface{}`

GetObjects returns the Objects field if non-nil, zero value otherwise.

### GetObjectsOk

`func (o *BulkImportPost200Response) GetObjectsOk() (*map[string]interface{}, bool)`

GetObjectsOk returns a tuple with the Objects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjects

`func (o *BulkImportPost200Response) SetObjects(v map[string]interface{})`

SetObjects sets Objects field to given value.

### HasObjects

`func (o *BulkImportPost200Response) HasObjects() bool`

HasObjects returns a boolean if a field has been set.

### SetObjectsNil

`func (o *BulkImportPost200Response) SetObjectsNil(b bool)`

 SetObjectsNil sets the value for Objects to be an explicit nil

### UnsetObjects
`func (o *BulkImportPost200Response) UnsetObjects()`

UnsetObjects ensures that no value is present for Objects, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



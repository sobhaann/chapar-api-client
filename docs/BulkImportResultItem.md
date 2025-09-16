# BulkImportResultItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tracking** | Pointer to **string** |  | [optional] 
**Reference** | Pointer to **int32** |  | [optional] 
**Status** | Pointer to **bool** |  | [optional] 
**Error** | Pointer to **string** |  | [optional] 

## Methods

### NewBulkImportResultItem

`func NewBulkImportResultItem() *BulkImportResultItem`

NewBulkImportResultItem instantiates a new BulkImportResultItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkImportResultItemWithDefaults

`func NewBulkImportResultItemWithDefaults() *BulkImportResultItem`

NewBulkImportResultItemWithDefaults instantiates a new BulkImportResultItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTracking

`func (o *BulkImportResultItem) GetTracking() string`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *BulkImportResultItem) GetTrackingOk() (*string, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *BulkImportResultItem) SetTracking(v string)`

SetTracking sets Tracking field to given value.

### HasTracking

`func (o *BulkImportResultItem) HasTracking() bool`

HasTracking returns a boolean if a field has been set.

### GetReference

`func (o *BulkImportResultItem) GetReference() int32`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *BulkImportResultItem) GetReferenceOk() (*int32, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *BulkImportResultItem) SetReference(v int32)`

SetReference sets Reference field to given value.

### HasReference

`func (o *BulkImportResultItem) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetStatus

`func (o *BulkImportResultItem) GetStatus() bool`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BulkImportResultItem) GetStatusOk() (*bool, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BulkImportResultItem) SetStatus(v bool)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *BulkImportResultItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetError

`func (o *BulkImportResultItem) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *BulkImportResultItem) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *BulkImportResultItem) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *BulkImportResultItem) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



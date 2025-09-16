# BulkImportResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tracking** | Pointer to **string** |  | [optional] 
**Reference** | Pointer to **int32** |  | [optional] 
**Status** | Pointer to **bool** |  | [optional] 
**Error** | Pointer to **string** |  | [optional] 

## Methods

### NewBulkImportResult

`func NewBulkImportResult() *BulkImportResult`

NewBulkImportResult instantiates a new BulkImportResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkImportResultWithDefaults

`func NewBulkImportResultWithDefaults() *BulkImportResult`

NewBulkImportResultWithDefaults instantiates a new BulkImportResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTracking

`func (o *BulkImportResult) GetTracking() string`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *BulkImportResult) GetTrackingOk() (*string, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *BulkImportResult) SetTracking(v string)`

SetTracking sets Tracking field to given value.

### HasTracking

`func (o *BulkImportResult) HasTracking() bool`

HasTracking returns a boolean if a field has been set.

### GetReference

`func (o *BulkImportResult) GetReference() int32`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *BulkImportResult) GetReferenceOk() (*int32, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *BulkImportResult) SetReference(v int32)`

SetReference sets Reference field to given value.

### HasReference

`func (o *BulkImportResult) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetStatus

`func (o *BulkImportResult) GetStatus() bool`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BulkImportResult) GetStatusOk() (*bool, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BulkImportResult) SetStatus(v bool)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *BulkImportResult) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetError

`func (o *BulkImportResult) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *BulkImportResult) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *BulkImportResult) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *BulkImportResult) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



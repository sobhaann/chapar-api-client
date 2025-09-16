# BulkHistoryEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Tracking** | Pointer to **string** |  | [optional] 

## Methods

### NewBulkHistoryEvent

`func NewBulkHistoryEvent() *BulkHistoryEvent`

NewBulkHistoryEvent instantiates a new BulkHistoryEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkHistoryEventWithDefaults

`func NewBulkHistoryEventWithDefaults() *BulkHistoryEvent`

NewBulkHistoryEventWithDefaults instantiates a new BulkHistoryEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *BulkHistoryEvent) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BulkHistoryEvent) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BulkHistoryEvent) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *BulkHistoryEvent) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTracking

`func (o *BulkHistoryEvent) GetTracking() string`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *BulkHistoryEvent) GetTrackingOk() (*string, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *BulkHistoryEvent) SetTracking(v string)`

SetTracking sets Tracking field to given value.

### HasTracking

`func (o *BulkHistoryEvent) HasTracking() bool`

HasTracking returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



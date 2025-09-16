# HistoryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TimestampDate** | Pointer to **int32** |  | [optional] 
**Date** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**StatusNote** | Pointer to **string** |  | [optional] 

## Methods

### NewHistoryItem

`func NewHistoryItem() *HistoryItem`

NewHistoryItem instantiates a new HistoryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoryItemWithDefaults

`func NewHistoryItemWithDefaults() *HistoryItem`

NewHistoryItemWithDefaults instantiates a new HistoryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTimestampDate

`func (o *HistoryItem) GetTimestampDate() int32`

GetTimestampDate returns the TimestampDate field if non-nil, zero value otherwise.

### GetTimestampDateOk

`func (o *HistoryItem) GetTimestampDateOk() (*int32, bool)`

GetTimestampDateOk returns a tuple with the TimestampDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestampDate

`func (o *HistoryItem) SetTimestampDate(v int32)`

SetTimestampDate sets TimestampDate field to given value.

### HasTimestampDate

`func (o *HistoryItem) HasTimestampDate() bool`

HasTimestampDate returns a boolean if a field has been set.

### GetDate

`func (o *HistoryItem) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *HistoryItem) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *HistoryItem) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *HistoryItem) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetStatus

`func (o *HistoryItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *HistoryItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *HistoryItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *HistoryItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetStatusNote

`func (o *HistoryItem) GetStatusNote() string`

GetStatusNote returns the StatusNote field if non-nil, zero value otherwise.

### GetStatusNoteOk

`func (o *HistoryItem) GetStatusNoteOk() (*string, bool)`

GetStatusNoteOk returns a tuple with the StatusNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusNote

`func (o *HistoryItem) SetStatusNote(v string)`

SetStatusNote sets StatusNote field to given value.

### HasStatusNote

`func (o *HistoryItem) HasStatusNote() bool`

HasStatusNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



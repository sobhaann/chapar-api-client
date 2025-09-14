# HistoryEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TimestampDate** | Pointer to **int32** |  | [optional] 
**Date** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**StatusNote** | Pointer to **string** |  | [optional] 

## Methods

### NewHistoryEvent

`func NewHistoryEvent() *HistoryEvent`

NewHistoryEvent instantiates a new HistoryEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoryEventWithDefaults

`func NewHistoryEventWithDefaults() *HistoryEvent`

NewHistoryEventWithDefaults instantiates a new HistoryEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTimestampDate

`func (o *HistoryEvent) GetTimestampDate() int32`

GetTimestampDate returns the TimestampDate field if non-nil, zero value otherwise.

### GetTimestampDateOk

`func (o *HistoryEvent) GetTimestampDateOk() (*int32, bool)`

GetTimestampDateOk returns a tuple with the TimestampDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestampDate

`func (o *HistoryEvent) SetTimestampDate(v int32)`

SetTimestampDate sets TimestampDate field to given value.

### HasTimestampDate

`func (o *HistoryEvent) HasTimestampDate() bool`

HasTimestampDate returns a boolean if a field has been set.

### GetDate

`func (o *HistoryEvent) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *HistoryEvent) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *HistoryEvent) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *HistoryEvent) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetStatus

`func (o *HistoryEvent) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *HistoryEvent) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *HistoryEvent) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *HistoryEvent) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetStatusNote

`func (o *HistoryEvent) GetStatusNote() string`

GetStatusNote returns the StatusNote field if non-nil, zero value otherwise.

### GetStatusNoteOk

`func (o *HistoryEvent) GetStatusNoteOk() (*string, bool)`

GetStatusNoteOk returns a tuple with the StatusNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusNote

`func (o *HistoryEvent) SetStatusNote(v string)`

SetStatusNote sets StatusNote field to given value.

### HasStatusNote

`func (o *HistoryEvent) HasStatusNote() bool`

HasStatusNote returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



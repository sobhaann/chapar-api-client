# TrackingHistoryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TimestampDate** | Pointer to **int32** |  | [optional] 
**Date** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Loc** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTrackingHistoryItem

`func NewTrackingHistoryItem() *TrackingHistoryItem`

NewTrackingHistoryItem instantiates a new TrackingHistoryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackingHistoryItemWithDefaults

`func NewTrackingHistoryItemWithDefaults() *TrackingHistoryItem`

NewTrackingHistoryItemWithDefaults instantiates a new TrackingHistoryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTimestampDate

`func (o *TrackingHistoryItem) GetTimestampDate() int32`

GetTimestampDate returns the TimestampDate field if non-nil, zero value otherwise.

### GetTimestampDateOk

`func (o *TrackingHistoryItem) GetTimestampDateOk() (*int32, bool)`

GetTimestampDateOk returns a tuple with the TimestampDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestampDate

`func (o *TrackingHistoryItem) SetTimestampDate(v int32)`

SetTimestampDate sets TimestampDate field to given value.

### HasTimestampDate

`func (o *TrackingHistoryItem) HasTimestampDate() bool`

HasTimestampDate returns a boolean if a field has been set.

### GetDate

`func (o *TrackingHistoryItem) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *TrackingHistoryItem) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *TrackingHistoryItem) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *TrackingHistoryItem) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetStatus

`func (o *TrackingHistoryItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TrackingHistoryItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TrackingHistoryItem) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TrackingHistoryItem) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetLoc

`func (o *TrackingHistoryItem) GetLoc() string`

GetLoc returns the Loc field if non-nil, zero value otherwise.

### GetLocOk

`func (o *TrackingHistoryItem) GetLocOk() (*string, bool)`

GetLocOk returns a tuple with the Loc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoc

`func (o *TrackingHistoryItem) SetLoc(v string)`

SetLoc sets Loc field to given value.

### HasLoc

`func (o *TrackingHistoryItem) HasLoc() bool`

HasLoc returns a boolean if a field has been set.

### SetLocNil

`func (o *TrackingHistoryItem) SetLocNil(b bool)`

 SetLocNil sets the value for Loc to be an explicit nil

### UnsetLoc
`func (o *TrackingHistoryItem) UnsetLoc()`

UnsetLoc ensures that no value is present for Loc, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



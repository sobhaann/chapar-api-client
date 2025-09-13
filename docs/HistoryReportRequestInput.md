# HistoryReportRequestInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**User** | [**User**](User.md) |  | 
**Date** | [**HistoryReportRequestInputDate**](HistoryReportRequestInputDate.md) |  | 
**MaximumRecords** | Pointer to **int32** |  | [optional] 

## Methods

### NewHistoryReportRequestInput

`func NewHistoryReportRequestInput(user User, date HistoryReportRequestInputDate, ) *HistoryReportRequestInput`

NewHistoryReportRequestInput instantiates a new HistoryReportRequestInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoryReportRequestInputWithDefaults

`func NewHistoryReportRequestInputWithDefaults() *HistoryReportRequestInput`

NewHistoryReportRequestInputWithDefaults instantiates a new HistoryReportRequestInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUser

`func (o *HistoryReportRequestInput) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *HistoryReportRequestInput) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *HistoryReportRequestInput) SetUser(v User)`

SetUser sets User field to given value.


### GetDate

`func (o *HistoryReportRequestInput) GetDate() HistoryReportRequestInputDate`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *HistoryReportRequestInput) GetDateOk() (*HistoryReportRequestInputDate, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *HistoryReportRequestInput) SetDate(v HistoryReportRequestInputDate)`

SetDate sets Date field to given value.


### GetMaximumRecords

`func (o *HistoryReportRequestInput) GetMaximumRecords() int32`

GetMaximumRecords returns the MaximumRecords field if non-nil, zero value otherwise.

### GetMaximumRecordsOk

`func (o *HistoryReportRequestInput) GetMaximumRecordsOk() (*int32, bool)`

GetMaximumRecordsOk returns a tuple with the MaximumRecords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximumRecords

`func (o *HistoryReportRequestInput) SetMaximumRecords(v int32)`

SetMaximumRecords sets MaximumRecords field to given value.

### HasMaximumRecords

`func (o *HistoryReportRequestInput) HasMaximumRecords() bool`

HasMaximumRecords returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



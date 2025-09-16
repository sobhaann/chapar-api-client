# HistoryReportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | **bool** |  | 
**Message** | Pointer to **NullableString** |  | [optional] 
**Objects** | [**HistoryReportObject**](HistoryReportObject.md) |  | 

## Methods

### NewHistoryReportResponse

`func NewHistoryReportResponse(result bool, objects HistoryReportObject, ) *HistoryReportResponse`

NewHistoryReportResponse instantiates a new HistoryReportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoryReportResponseWithDefaults

`func NewHistoryReportResponseWithDefaults() *HistoryReportResponse`

NewHistoryReportResponseWithDefaults instantiates a new HistoryReportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *HistoryReportResponse) GetResult() bool`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *HistoryReportResponse) GetResultOk() (*bool, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *HistoryReportResponse) SetResult(v bool)`

SetResult sets Result field to given value.


### GetMessage

`func (o *HistoryReportResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *HistoryReportResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *HistoryReportResponse) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *HistoryReportResponse) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *HistoryReportResponse) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *HistoryReportResponse) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetObjects

`func (o *HistoryReportResponse) GetObjects() HistoryReportObject`

GetObjects returns the Objects field if non-nil, zero value otherwise.

### GetObjectsOk

`func (o *HistoryReportResponse) GetObjectsOk() (*HistoryReportObject, bool)`

GetObjectsOk returns a tuple with the Objects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjects

`func (o *HistoryReportResponse) SetObjects(v HistoryReportObject)`

SetObjects sets Objects field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



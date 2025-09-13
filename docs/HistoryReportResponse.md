# HistoryReportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Data** | Pointer to [**HistoryReportData**](HistoryReportData.md) |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewHistoryReportResponse

`func NewHistoryReportResponse() *HistoryReportResponse`

NewHistoryReportResponse instantiates a new HistoryReportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoryReportResponseWithDefaults

`func NewHistoryReportResponseWithDefaults() *HistoryReportResponse`

NewHistoryReportResponseWithDefaults instantiates a new HistoryReportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *HistoryReportResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *HistoryReportResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *HistoryReportResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *HistoryReportResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetData

`func (o *HistoryReportResponse) GetData() HistoryReportData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *HistoryReportResponse) GetDataOk() (*HistoryReportData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *HistoryReportResponse) SetData(v HistoryReportData)`

SetData sets Data field to given value.

### HasData

`func (o *HistoryReportResponse) HasData() bool`

HasData returns a boolean if a field has been set.

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

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



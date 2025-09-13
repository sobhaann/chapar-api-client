# BulkHistoryReportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Data** | Pointer to [**BulkHistoryReportData**](BulkHistoryReportData.md) |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewBulkHistoryReportResponse

`func NewBulkHistoryReportResponse() *BulkHistoryReportResponse`

NewBulkHistoryReportResponse instantiates a new BulkHistoryReportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkHistoryReportResponseWithDefaults

`func NewBulkHistoryReportResponseWithDefaults() *BulkHistoryReportResponse`

NewBulkHistoryReportResponseWithDefaults instantiates a new BulkHistoryReportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *BulkHistoryReportResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *BulkHistoryReportResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *BulkHistoryReportResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *BulkHistoryReportResponse) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetData

`func (o *BulkHistoryReportResponse) GetData() BulkHistoryReportData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *BulkHistoryReportResponse) GetDataOk() (*BulkHistoryReportData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *BulkHistoryReportResponse) SetData(v BulkHistoryReportData)`

SetData sets Data field to given value.

### HasData

`func (o *BulkHistoryReportResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMessage

`func (o *BulkHistoryReportResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *BulkHistoryReportResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *BulkHistoryReportResponse) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *BulkHistoryReportResponse) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *BulkHistoryReportResponse) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *BulkHistoryReportResponse) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



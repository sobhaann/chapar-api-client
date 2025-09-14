# BulkHistoryReportPost200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Data** | Pointer to [**BulkHistoryReportData**](BulkHistoryReportData.md) |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewBulkHistoryReportPost200Response

`func NewBulkHistoryReportPost200Response() *BulkHistoryReportPost200Response`

NewBulkHistoryReportPost200Response instantiates a new BulkHistoryReportPost200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkHistoryReportPost200ResponseWithDefaults

`func NewBulkHistoryReportPost200ResponseWithDefaults() *BulkHistoryReportPost200Response`

NewBulkHistoryReportPost200ResponseWithDefaults instantiates a new BulkHistoryReportPost200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *BulkHistoryReportPost200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *BulkHistoryReportPost200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *BulkHistoryReportPost200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *BulkHistoryReportPost200Response) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetData

`func (o *BulkHistoryReportPost200Response) GetData() BulkHistoryReportData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *BulkHistoryReportPost200Response) GetDataOk() (*BulkHistoryReportData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *BulkHistoryReportPost200Response) SetData(v BulkHistoryReportData)`

SetData sets Data field to given value.

### HasData

`func (o *BulkHistoryReportPost200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMessage

`func (o *BulkHistoryReportPost200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *BulkHistoryReportPost200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *BulkHistoryReportPost200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *BulkHistoryReportPost200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *BulkHistoryReportPost200Response) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *BulkHistoryReportPost200Response) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



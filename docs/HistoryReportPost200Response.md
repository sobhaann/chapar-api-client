# HistoryReportPost200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Data** | Pointer to [**HistoryReportData**](HistoryReportData.md) |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewHistoryReportPost200Response

`func NewHistoryReportPost200Response() *HistoryReportPost200Response`

NewHistoryReportPost200Response instantiates a new HistoryReportPost200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoryReportPost200ResponseWithDefaults

`func NewHistoryReportPost200ResponseWithDefaults() *HistoryReportPost200Response`

NewHistoryReportPost200ResponseWithDefaults instantiates a new HistoryReportPost200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *HistoryReportPost200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *HistoryReportPost200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *HistoryReportPost200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *HistoryReportPost200Response) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetData

`func (o *HistoryReportPost200Response) GetData() HistoryReportData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *HistoryReportPost200Response) GetDataOk() (*HistoryReportData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *HistoryReportPost200Response) SetData(v HistoryReportData)`

SetData sets Data field to given value.

### HasData

`func (o *HistoryReportPost200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMessage

`func (o *HistoryReportPost200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *HistoryReportPost200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *HistoryReportPost200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *HistoryReportPost200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *HistoryReportPost200Response) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *HistoryReportPost200Response) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



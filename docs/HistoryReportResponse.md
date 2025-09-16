# HistoryReportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cn** | Pointer to [**HistoryConsignmentNote**](HistoryConsignmentNote.md) |  | [optional] 
**Receiver** | Pointer to [**HistoryContact**](HistoryContact.md) |  | [optional] 
**Financial** | Pointer to [**Financial**](Financial.md) |  | [optional] 
**History** | Pointer to [**[]HistoryItem**](HistoryItem.md) |  | [optional] 

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

### GetCn

`func (o *HistoryReportResponse) GetCn() HistoryConsignmentNote`

GetCn returns the Cn field if non-nil, zero value otherwise.

### GetCnOk

`func (o *HistoryReportResponse) GetCnOk() (*HistoryConsignmentNote, bool)`

GetCnOk returns a tuple with the Cn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCn

`func (o *HistoryReportResponse) SetCn(v HistoryConsignmentNote)`

SetCn sets Cn field to given value.

### HasCn

`func (o *HistoryReportResponse) HasCn() bool`

HasCn returns a boolean if a field has been set.

### GetReceiver

`func (o *HistoryReportResponse) GetReceiver() HistoryContact`

GetReceiver returns the Receiver field if non-nil, zero value otherwise.

### GetReceiverOk

`func (o *HistoryReportResponse) GetReceiverOk() (*HistoryContact, bool)`

GetReceiverOk returns a tuple with the Receiver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiver

`func (o *HistoryReportResponse) SetReceiver(v HistoryContact)`

SetReceiver sets Receiver field to given value.

### HasReceiver

`func (o *HistoryReportResponse) HasReceiver() bool`

HasReceiver returns a boolean if a field has been set.

### GetFinancial

`func (o *HistoryReportResponse) GetFinancial() Financial`

GetFinancial returns the Financial field if non-nil, zero value otherwise.

### GetFinancialOk

`func (o *HistoryReportResponse) GetFinancialOk() (*Financial, bool)`

GetFinancialOk returns a tuple with the Financial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinancial

`func (o *HistoryReportResponse) SetFinancial(v Financial)`

SetFinancial sets Financial field to given value.

### HasFinancial

`func (o *HistoryReportResponse) HasFinancial() bool`

HasFinancial returns a boolean if a field has been set.

### GetHistory

`func (o *HistoryReportResponse) GetHistory() []HistoryItem`

GetHistory returns the History field if non-nil, zero value otherwise.

### GetHistoryOk

`func (o *HistoryReportResponse) GetHistoryOk() (*[]HistoryItem, bool)`

GetHistoryOk returns a tuple with the History field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistory

`func (o *HistoryReportResponse) SetHistory(v []HistoryItem)`

SetHistory sets History field to given value.

### HasHistory

`func (o *HistoryReportResponse) HasHistory() bool`

HasHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



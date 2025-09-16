# HistoryReportObject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cn** | [**ConsignmentNote**](ConsignmentNote.md) |  | 
**Receiver** | [**ReceiverInfo**](ReceiverInfo.md) |  | 
**Financial** | [**FinancialInfo**](FinancialInfo.md) |  | 
**History** | [**[]HistoryEvent**](HistoryEvent.md) |  | 

## Methods

### NewHistoryReportObject

`func NewHistoryReportObject(cn ConsignmentNote, receiver ReceiverInfo, financial FinancialInfo, history []HistoryEvent, ) *HistoryReportObject`

NewHistoryReportObject instantiates a new HistoryReportObject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHistoryReportObjectWithDefaults

`func NewHistoryReportObjectWithDefaults() *HistoryReportObject`

NewHistoryReportObjectWithDefaults instantiates a new HistoryReportObject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCn

`func (o *HistoryReportObject) GetCn() ConsignmentNote`

GetCn returns the Cn field if non-nil, zero value otherwise.

### GetCnOk

`func (o *HistoryReportObject) GetCnOk() (*ConsignmentNote, bool)`

GetCnOk returns a tuple with the Cn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCn

`func (o *HistoryReportObject) SetCn(v ConsignmentNote)`

SetCn sets Cn field to given value.


### GetReceiver

`func (o *HistoryReportObject) GetReceiver() ReceiverInfo`

GetReceiver returns the Receiver field if non-nil, zero value otherwise.

### GetReceiverOk

`func (o *HistoryReportObject) GetReceiverOk() (*ReceiverInfo, bool)`

GetReceiverOk returns a tuple with the Receiver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiver

`func (o *HistoryReportObject) SetReceiver(v ReceiverInfo)`

SetReceiver sets Receiver field to given value.


### GetFinancial

`func (o *HistoryReportObject) GetFinancial() FinancialInfo`

GetFinancial returns the Financial field if non-nil, zero value otherwise.

### GetFinancialOk

`func (o *HistoryReportObject) GetFinancialOk() (*FinancialInfo, bool)`

GetFinancialOk returns a tuple with the Financial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinancial

`func (o *HistoryReportObject) SetFinancial(v FinancialInfo)`

SetFinancial sets Financial field to given value.


### GetHistory

`func (o *HistoryReportObject) GetHistory() []HistoryEvent`

GetHistory returns the History field if non-nil, zero value otherwise.

### GetHistoryOk

`func (o *HistoryReportObject) GetHistoryOk() (*[]HistoryEvent, bool)`

GetHistoryOk returns a tuple with the History field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistory

`func (o *HistoryReportObject) SetHistory(v []HistoryEvent)`

SetHistory sets History field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



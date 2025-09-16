# BulkItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cn** | Pointer to [**BulkConsignmentNote**](BulkConsignmentNote.md) |  | [optional] 
**Receiver** | Pointer to [**Contact**](Contact.md) |  | [optional] 
**Sender** | Pointer to [**Contact**](Contact.md) |  | [optional] 

## Methods

### NewBulkItem

`func NewBulkItem() *BulkItem`

NewBulkItem instantiates a new BulkItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkItemWithDefaults

`func NewBulkItemWithDefaults() *BulkItem`

NewBulkItemWithDefaults instantiates a new BulkItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCn

`func (o *BulkItem) GetCn() BulkConsignmentNote`

GetCn returns the Cn field if non-nil, zero value otherwise.

### GetCnOk

`func (o *BulkItem) GetCnOk() (*BulkConsignmentNote, bool)`

GetCnOk returns a tuple with the Cn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCn

`func (o *BulkItem) SetCn(v BulkConsignmentNote)`

SetCn sets Cn field to given value.

### HasCn

`func (o *BulkItem) HasCn() bool`

HasCn returns a boolean if a field has been set.

### GetReceiver

`func (o *BulkItem) GetReceiver() Contact`

GetReceiver returns the Receiver field if non-nil, zero value otherwise.

### GetReceiverOk

`func (o *BulkItem) GetReceiverOk() (*Contact, bool)`

GetReceiverOk returns a tuple with the Receiver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiver

`func (o *BulkItem) SetReceiver(v Contact)`

SetReceiver sets Receiver field to given value.

### HasReceiver

`func (o *BulkItem) HasReceiver() bool`

HasReceiver returns a boolean if a field has been set.

### GetSender

`func (o *BulkItem) GetSender() Contact`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *BulkItem) GetSenderOk() (*Contact, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *BulkItem) SetSender(v Contact)`

SetSender sets Sender field to given value.

### HasSender

`func (o *BulkItem) HasSender() bool`

HasSender returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



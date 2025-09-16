# BulkHistoryReportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | **bool** |  | 
**Message** | Pointer to **NullableString** |  | [optional] 
**Objects** | [**BulkHistoryReportObject**](BulkHistoryReportObject.md) |  | 

## Methods

### NewBulkHistoryReportResponse

`func NewBulkHistoryReportResponse(result bool, objects BulkHistoryReportObject, ) *BulkHistoryReportResponse`

NewBulkHistoryReportResponse instantiates a new BulkHistoryReportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkHistoryReportResponseWithDefaults

`func NewBulkHistoryReportResponseWithDefaults() *BulkHistoryReportResponse`

NewBulkHistoryReportResponseWithDefaults instantiates a new BulkHistoryReportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *BulkHistoryReportResponse) GetResult() bool`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *BulkHistoryReportResponse) GetResultOk() (*bool, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *BulkHistoryReportResponse) SetResult(v bool)`

SetResult sets Result field to given value.


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
### GetObjects

`func (o *BulkHistoryReportResponse) GetObjects() BulkHistoryReportObject`

GetObjects returns the Objects field if non-nil, zero value otherwise.

### GetObjectsOk

`func (o *BulkHistoryReportResponse) GetObjectsOk() (*BulkHistoryReportObject, bool)`

GetObjectsOk returns a tuple with the Objects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjects

`func (o *BulkHistoryReportResponse) SetObjects(v BulkHistoryReportObject)`

SetObjects sets Objects field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



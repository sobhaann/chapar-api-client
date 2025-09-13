# BulkHistoryReportRequestInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**User** | [**User**](User.md) |  | 
**Bulk** | **[]string** |  | 

## Methods

### NewBulkHistoryReportRequestInput

`func NewBulkHistoryReportRequestInput(user User, bulk []string, ) *BulkHistoryReportRequestInput`

NewBulkHistoryReportRequestInput instantiates a new BulkHistoryReportRequestInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkHistoryReportRequestInputWithDefaults

`func NewBulkHistoryReportRequestInputWithDefaults() *BulkHistoryReportRequestInput`

NewBulkHistoryReportRequestInputWithDefaults instantiates a new BulkHistoryReportRequestInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUser

`func (o *BulkHistoryReportRequestInput) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *BulkHistoryReportRequestInput) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *BulkHistoryReportRequestInput) SetUser(v User)`

SetUser sets User field to given value.


### GetBulk

`func (o *BulkHistoryReportRequestInput) GetBulk() []string`

GetBulk returns the Bulk field if non-nil, zero value otherwise.

### GetBulkOk

`func (o *BulkHistoryReportRequestInput) GetBulkOk() (*[]string, bool)`

GetBulkOk returns a tuple with the Bulk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBulk

`func (o *BulkHistoryReportRequestInput) SetBulk(v []string)`

SetBulk sets Bulk field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



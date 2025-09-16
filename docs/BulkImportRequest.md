# BulkImportRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**User** | Pointer to [**User**](User.md) |  | [optional] 
**Bulk** | Pointer to [**[]BulkItem**](BulkItem.md) |  | [optional] 

## Methods

### NewBulkImportRequest

`func NewBulkImportRequest() *BulkImportRequest`

NewBulkImportRequest instantiates a new BulkImportRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkImportRequestWithDefaults

`func NewBulkImportRequestWithDefaults() *BulkImportRequest`

NewBulkImportRequestWithDefaults instantiates a new BulkImportRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUser

`func (o *BulkImportRequest) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *BulkImportRequest) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *BulkImportRequest) SetUser(v User)`

SetUser sets User field to given value.

### HasUser

`func (o *BulkImportRequest) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetBulk

`func (o *BulkImportRequest) GetBulk() []BulkItem`

GetBulk returns the Bulk field if non-nil, zero value otherwise.

### GetBulkOk

`func (o *BulkImportRequest) GetBulkOk() (*[]BulkItem, bool)`

GetBulkOk returns a tuple with the Bulk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBulk

`func (o *BulkImportRequest) SetBulk(v []BulkItem)`

SetBulk sets Bulk field to given value.

### HasBulk

`func (o *BulkImportRequest) HasBulk() bool`

HasBulk returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



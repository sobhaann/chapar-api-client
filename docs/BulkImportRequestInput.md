# BulkImportRequestInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**User** | [**User**](User.md) |  | 
**Bulk** | **[]map[string]interface{}** |  | 

## Methods

### NewBulkImportRequestInput

`func NewBulkImportRequestInput(user User, bulk []map[string]interface{}, ) *BulkImportRequestInput`

NewBulkImportRequestInput instantiates a new BulkImportRequestInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkImportRequestInputWithDefaults

`func NewBulkImportRequestInputWithDefaults() *BulkImportRequestInput`

NewBulkImportRequestInputWithDefaults instantiates a new BulkImportRequestInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUser

`func (o *BulkImportRequestInput) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *BulkImportRequestInput) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *BulkImportRequestInput) SetUser(v User)`

SetUser sets User field to given value.


### GetBulk

`func (o *BulkImportRequestInput) GetBulk() []map[string]interface{}`

GetBulk returns the Bulk field if non-nil, zero value otherwise.

### GetBulkOk

`func (o *BulkImportRequestInput) GetBulkOk() (*[]map[string]interface{}, bool)`

GetBulkOk returns a tuple with the Bulk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBulk

`func (o *BulkImportRequestInput) SetBulk(v []map[string]interface{})`

SetBulk sets Bulk field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



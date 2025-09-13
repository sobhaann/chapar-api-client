# CancelPickupRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**User** | [**User**](User.md) |  | 
**ConsignmentNo** | **string** |  | 
**Reason** | Pointer to **string** |  | [optional] 

## Methods

### NewCancelPickupRequest

`func NewCancelPickupRequest(user User, consignmentNo string, ) *CancelPickupRequest`

NewCancelPickupRequest instantiates a new CancelPickupRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCancelPickupRequestWithDefaults

`func NewCancelPickupRequestWithDefaults() *CancelPickupRequest`

NewCancelPickupRequestWithDefaults instantiates a new CancelPickupRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUser

`func (o *CancelPickupRequest) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *CancelPickupRequest) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *CancelPickupRequest) SetUser(v User)`

SetUser sets User field to given value.


### GetConsignmentNo

`func (o *CancelPickupRequest) GetConsignmentNo() string`

GetConsignmentNo returns the ConsignmentNo field if non-nil, zero value otherwise.

### GetConsignmentNoOk

`func (o *CancelPickupRequest) GetConsignmentNoOk() (*string, bool)`

GetConsignmentNoOk returns a tuple with the ConsignmentNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsignmentNo

`func (o *CancelPickupRequest) SetConsignmentNo(v string)`

SetConsignmentNo sets ConsignmentNo field to given value.


### GetReason

`func (o *CancelPickupRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *CancelPickupRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *CancelPickupRequest) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *CancelPickupRequest) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



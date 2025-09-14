# CancelPickupRequestInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**User** | [**User**](User.md) |  | 
**ConsignmentNo** | **string** |  | 
**Reason** | Pointer to **string** |  | [optional] 

## Methods

### NewCancelPickupRequestInput

`func NewCancelPickupRequestInput(user User, consignmentNo string, ) *CancelPickupRequestInput`

NewCancelPickupRequestInput instantiates a new CancelPickupRequestInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCancelPickupRequestInputWithDefaults

`func NewCancelPickupRequestInputWithDefaults() *CancelPickupRequestInput`

NewCancelPickupRequestInputWithDefaults instantiates a new CancelPickupRequestInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUser

`func (o *CancelPickupRequestInput) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *CancelPickupRequestInput) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *CancelPickupRequestInput) SetUser(v User)`

SetUser sets User field to given value.


### GetConsignmentNo

`func (o *CancelPickupRequestInput) GetConsignmentNo() string`

GetConsignmentNo returns the ConsignmentNo field if non-nil, zero value otherwise.

### GetConsignmentNoOk

`func (o *CancelPickupRequestInput) GetConsignmentNoOk() (*string, bool)`

GetConsignmentNoOk returns a tuple with the ConsignmentNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConsignmentNo

`func (o *CancelPickupRequestInput) SetConsignmentNo(v string)`

SetConsignmentNo sets ConsignmentNo field to given value.


### GetReason

`func (o *CancelPickupRequestInput) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *CancelPickupRequestInput) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *CancelPickupRequestInput) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *CancelPickupRequestInput) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



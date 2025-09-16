# OrderDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Origin** | **string** |  | 
**Destination** | **string** |  | 
**Weight** | **string** |  | 
**Value** | **string** |  | 
**Method** | **string** |  | 
**SenderCode** | Pointer to **NullableString** |  | [optional] 
**ReceiverCode** | Pointer to **NullableString** |  | [optional] 
**Cod** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewOrderDetails

`func NewOrderDetails(origin string, destination string, weight string, value string, method string, ) *OrderDetails`

NewOrderDetails instantiates a new OrderDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderDetailsWithDefaults

`func NewOrderDetailsWithDefaults() *OrderDetails`

NewOrderDetailsWithDefaults instantiates a new OrderDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrigin

`func (o *OrderDetails) GetOrigin() string`

GetOrigin returns the Origin field if non-nil, zero value otherwise.

### GetOriginOk

`func (o *OrderDetails) GetOriginOk() (*string, bool)`

GetOriginOk returns a tuple with the Origin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigin

`func (o *OrderDetails) SetOrigin(v string)`

SetOrigin sets Origin field to given value.


### GetDestination

`func (o *OrderDetails) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *OrderDetails) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *OrderDetails) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetWeight

`func (o *OrderDetails) GetWeight() string`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *OrderDetails) GetWeightOk() (*string, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *OrderDetails) SetWeight(v string)`

SetWeight sets Weight field to given value.


### GetValue

`func (o *OrderDetails) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *OrderDetails) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *OrderDetails) SetValue(v string)`

SetValue sets Value field to given value.


### GetMethod

`func (o *OrderDetails) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *OrderDetails) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *OrderDetails) SetMethod(v string)`

SetMethod sets Method field to given value.


### GetSenderCode

`func (o *OrderDetails) GetSenderCode() string`

GetSenderCode returns the SenderCode field if non-nil, zero value otherwise.

### GetSenderCodeOk

`func (o *OrderDetails) GetSenderCodeOk() (*string, bool)`

GetSenderCodeOk returns a tuple with the SenderCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderCode

`func (o *OrderDetails) SetSenderCode(v string)`

SetSenderCode sets SenderCode field to given value.

### HasSenderCode

`func (o *OrderDetails) HasSenderCode() bool`

HasSenderCode returns a boolean if a field has been set.

### SetSenderCodeNil

`func (o *OrderDetails) SetSenderCodeNil(b bool)`

 SetSenderCodeNil sets the value for SenderCode to be an explicit nil

### UnsetSenderCode
`func (o *OrderDetails) UnsetSenderCode()`

UnsetSenderCode ensures that no value is present for SenderCode, not even an explicit nil
### GetReceiverCode

`func (o *OrderDetails) GetReceiverCode() string`

GetReceiverCode returns the ReceiverCode field if non-nil, zero value otherwise.

### GetReceiverCodeOk

`func (o *OrderDetails) GetReceiverCodeOk() (*string, bool)`

GetReceiverCodeOk returns a tuple with the ReceiverCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiverCode

`func (o *OrderDetails) SetReceiverCode(v string)`

SetReceiverCode sets ReceiverCode field to given value.

### HasReceiverCode

`func (o *OrderDetails) HasReceiverCode() bool`

HasReceiverCode returns a boolean if a field has been set.

### SetReceiverCodeNil

`func (o *OrderDetails) SetReceiverCodeNil(b bool)`

 SetReceiverCodeNil sets the value for ReceiverCode to be an explicit nil

### UnsetReceiverCode
`func (o *OrderDetails) UnsetReceiverCode()`

UnsetReceiverCode ensures that no value is present for ReceiverCode, not even an explicit nil
### GetCod

`func (o *OrderDetails) GetCod() string`

GetCod returns the Cod field if non-nil, zero value otherwise.

### GetCodOk

`func (o *OrderDetails) GetCodOk() (*string, bool)`

GetCodOk returns a tuple with the Cod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCod

`func (o *OrderDetails) SetCod(v string)`

SetCod sets Cod field to given value.

### HasCod

`func (o *OrderDetails) HasCod() bool`

HasCod returns a boolean if a field has been set.

### SetCodNil

`func (o *OrderDetails) SetCodNil(b bool)`

 SetCodNil sets the value for Cod to be an explicit nil

### UnsetCod
`func (o *OrderDetails) UnsetCod()`

UnsetCod ensures that no value is present for Cod, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



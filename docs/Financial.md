# Financial

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeliveryCharge** | Pointer to **string** |  | [optional] 
**TotalCharge** | Pointer to **int32** |  | [optional] 

## Methods

### NewFinancial

`func NewFinancial() *Financial`

NewFinancial instantiates a new Financial object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFinancialWithDefaults

`func NewFinancialWithDefaults() *Financial`

NewFinancialWithDefaults instantiates a new Financial object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliveryCharge

`func (o *Financial) GetDeliveryCharge() string`

GetDeliveryCharge returns the DeliveryCharge field if non-nil, zero value otherwise.

### GetDeliveryChargeOk

`func (o *Financial) GetDeliveryChargeOk() (*string, bool)`

GetDeliveryChargeOk returns a tuple with the DeliveryCharge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryCharge

`func (o *Financial) SetDeliveryCharge(v string)`

SetDeliveryCharge sets DeliveryCharge field to given value.

### HasDeliveryCharge

`func (o *Financial) HasDeliveryCharge() bool`

HasDeliveryCharge returns a boolean if a field has been set.

### GetTotalCharge

`func (o *Financial) GetTotalCharge() int32`

GetTotalCharge returns the TotalCharge field if non-nil, zero value otherwise.

### GetTotalChargeOk

`func (o *Financial) GetTotalChargeOk() (*int32, bool)`

GetTotalChargeOk returns a tuple with the TotalCharge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCharge

`func (o *Financial) SetTotalCharge(v int32)`

SetTotalCharge sets TotalCharge field to given value.

### HasTotalCharge

`func (o *Financial) HasTotalCharge() bool`

HasTotalCharge returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



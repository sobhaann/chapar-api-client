# TrackingObjectOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeliveredTo** | Pointer to **NullableString** |  | [optional] 
**DeliveryTime** | Pointer to **NullableString** |  | [optional] 
**Signature** | Pointer to **NullableString** |  | [optional] 
**History** | Pointer to [**[]TrackingHistoryItem**](TrackingHistoryItem.md) |  | [optional] 

## Methods

### NewTrackingObjectOrder

`func NewTrackingObjectOrder() *TrackingObjectOrder`

NewTrackingObjectOrder instantiates a new TrackingObjectOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackingObjectOrderWithDefaults

`func NewTrackingObjectOrderWithDefaults() *TrackingObjectOrder`

NewTrackingObjectOrderWithDefaults instantiates a new TrackingObjectOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliveredTo

`func (o *TrackingObjectOrder) GetDeliveredTo() string`

GetDeliveredTo returns the DeliveredTo field if non-nil, zero value otherwise.

### GetDeliveredToOk

`func (o *TrackingObjectOrder) GetDeliveredToOk() (*string, bool)`

GetDeliveredToOk returns a tuple with the DeliveredTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveredTo

`func (o *TrackingObjectOrder) SetDeliveredTo(v string)`

SetDeliveredTo sets DeliveredTo field to given value.

### HasDeliveredTo

`func (o *TrackingObjectOrder) HasDeliveredTo() bool`

HasDeliveredTo returns a boolean if a field has been set.

### SetDeliveredToNil

`func (o *TrackingObjectOrder) SetDeliveredToNil(b bool)`

 SetDeliveredToNil sets the value for DeliveredTo to be an explicit nil

### UnsetDeliveredTo
`func (o *TrackingObjectOrder) UnsetDeliveredTo()`

UnsetDeliveredTo ensures that no value is present for DeliveredTo, not even an explicit nil
### GetDeliveryTime

`func (o *TrackingObjectOrder) GetDeliveryTime() string`

GetDeliveryTime returns the DeliveryTime field if non-nil, zero value otherwise.

### GetDeliveryTimeOk

`func (o *TrackingObjectOrder) GetDeliveryTimeOk() (*string, bool)`

GetDeliveryTimeOk returns a tuple with the DeliveryTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryTime

`func (o *TrackingObjectOrder) SetDeliveryTime(v string)`

SetDeliveryTime sets DeliveryTime field to given value.

### HasDeliveryTime

`func (o *TrackingObjectOrder) HasDeliveryTime() bool`

HasDeliveryTime returns a boolean if a field has been set.

### SetDeliveryTimeNil

`func (o *TrackingObjectOrder) SetDeliveryTimeNil(b bool)`

 SetDeliveryTimeNil sets the value for DeliveryTime to be an explicit nil

### UnsetDeliveryTime
`func (o *TrackingObjectOrder) UnsetDeliveryTime()`

UnsetDeliveryTime ensures that no value is present for DeliveryTime, not even an explicit nil
### GetSignature

`func (o *TrackingObjectOrder) GetSignature() string`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *TrackingObjectOrder) GetSignatureOk() (*string, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *TrackingObjectOrder) SetSignature(v string)`

SetSignature sets Signature field to given value.

### HasSignature

`func (o *TrackingObjectOrder) HasSignature() bool`

HasSignature returns a boolean if a field has been set.

### SetSignatureNil

`func (o *TrackingObjectOrder) SetSignatureNil(b bool)`

 SetSignatureNil sets the value for Signature to be an explicit nil

### UnsetSignature
`func (o *TrackingObjectOrder) UnsetSignature()`

UnsetSignature ensures that no value is present for Signature, not even an explicit nil
### GetHistory

`func (o *TrackingObjectOrder) GetHistory() []TrackingHistoryItem`

GetHistory returns the History field if non-nil, zero value otherwise.

### GetHistoryOk

`func (o *TrackingObjectOrder) GetHistoryOk() (*[]TrackingHistoryItem, bool)`

GetHistoryOk returns a tuple with the History field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistory

`func (o *TrackingObjectOrder) SetHistory(v []TrackingHistoryItem)`

SetHistory sets History field to given value.

### HasHistory

`func (o *TrackingObjectOrder) HasHistory() bool`

HasHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



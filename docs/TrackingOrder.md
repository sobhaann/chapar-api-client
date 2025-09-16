# TrackingOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeliveredTo** | Pointer to **string** |  | [optional] 
**DeliveryTime** | Pointer to **string** |  | [optional] 
**Signature** | Pointer to **string** |  | [optional] 
**Geo** | Pointer to [**Geo**](Geo.md) |  | [optional] 
**History** | Pointer to [**[]TrackingHistoryItem**](TrackingHistoryItem.md) |  | [optional] 

## Methods

### NewTrackingOrder

`func NewTrackingOrder() *TrackingOrder`

NewTrackingOrder instantiates a new TrackingOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackingOrderWithDefaults

`func NewTrackingOrderWithDefaults() *TrackingOrder`

NewTrackingOrderWithDefaults instantiates a new TrackingOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliveredTo

`func (o *TrackingOrder) GetDeliveredTo() string`

GetDeliveredTo returns the DeliveredTo field if non-nil, zero value otherwise.

### GetDeliveredToOk

`func (o *TrackingOrder) GetDeliveredToOk() (*string, bool)`

GetDeliveredToOk returns a tuple with the DeliveredTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveredTo

`func (o *TrackingOrder) SetDeliveredTo(v string)`

SetDeliveredTo sets DeliveredTo field to given value.

### HasDeliveredTo

`func (o *TrackingOrder) HasDeliveredTo() bool`

HasDeliveredTo returns a boolean if a field has been set.

### GetDeliveryTime

`func (o *TrackingOrder) GetDeliveryTime() string`

GetDeliveryTime returns the DeliveryTime field if non-nil, zero value otherwise.

### GetDeliveryTimeOk

`func (o *TrackingOrder) GetDeliveryTimeOk() (*string, bool)`

GetDeliveryTimeOk returns a tuple with the DeliveryTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryTime

`func (o *TrackingOrder) SetDeliveryTime(v string)`

SetDeliveryTime sets DeliveryTime field to given value.

### HasDeliveryTime

`func (o *TrackingOrder) HasDeliveryTime() bool`

HasDeliveryTime returns a boolean if a field has been set.

### GetSignature

`func (o *TrackingOrder) GetSignature() string`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *TrackingOrder) GetSignatureOk() (*string, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *TrackingOrder) SetSignature(v string)`

SetSignature sets Signature field to given value.

### HasSignature

`func (o *TrackingOrder) HasSignature() bool`

HasSignature returns a boolean if a field has been set.

### GetGeo

`func (o *TrackingOrder) GetGeo() Geo`

GetGeo returns the Geo field if non-nil, zero value otherwise.

### GetGeoOk

`func (o *TrackingOrder) GetGeoOk() (*Geo, bool)`

GetGeoOk returns a tuple with the Geo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeo

`func (o *TrackingOrder) SetGeo(v Geo)`

SetGeo sets Geo field to given value.

### HasGeo

`func (o *TrackingOrder) HasGeo() bool`

HasGeo returns a boolean if a field has been set.

### GetHistory

`func (o *TrackingOrder) GetHistory() []TrackingHistoryItem`

GetHistory returns the History field if non-nil, zero value otherwise.

### GetHistoryOk

`func (o *TrackingOrder) GetHistoryOk() (*[]TrackingHistoryItem, bool)`

GetHistoryOk returns a tuple with the History field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistory

`func (o *TrackingOrder) SetHistory(v []TrackingHistoryItem)`

SetHistory sets History field to given value.

### HasHistory

`func (o *TrackingOrder) HasHistory() bool`

HasHistory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



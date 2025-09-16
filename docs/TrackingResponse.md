# TrackingResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to [**TrackingOrder**](TrackingOrder.md) |  | [optional] 

## Methods

### NewTrackingResponse

`func NewTrackingResponse() *TrackingResponse`

NewTrackingResponse instantiates a new TrackingResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackingResponseWithDefaults

`func NewTrackingResponseWithDefaults() *TrackingResponse`

NewTrackingResponseWithDefaults instantiates a new TrackingResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *TrackingResponse) GetOrder() TrackingOrder`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *TrackingResponse) GetOrderOk() (*TrackingOrder, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *TrackingResponse) SetOrder(v TrackingOrder)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *TrackingResponse) HasOrder() bool`

HasOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



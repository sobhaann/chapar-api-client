# CallbackPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Location** | Pointer to [**CallbackLocation**](CallbackLocation.md) |  | [optional] 
**Date** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Comments** | Pointer to **string** |  | [optional] 

## Methods

### NewCallbackPayload

`func NewCallbackPayload() *CallbackPayload`

NewCallbackPayload instantiates a new CallbackPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCallbackPayloadWithDefaults

`func NewCallbackPayloadWithDefaults() *CallbackPayload`

NewCallbackPayloadWithDefaults instantiates a new CallbackPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLocation

`func (o *CallbackPayload) GetLocation() CallbackLocation`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *CallbackPayload) GetLocationOk() (*CallbackLocation, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *CallbackPayload) SetLocation(v CallbackLocation)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *CallbackPayload) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetDate

`func (o *CallbackPayload) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *CallbackPayload) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *CallbackPayload) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *CallbackPayload) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetStatus

`func (o *CallbackPayload) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CallbackPayload) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CallbackPayload) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CallbackPayload) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetComments

`func (o *CallbackPayload) GetComments() string`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *CallbackPayload) GetCommentsOk() (*string, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *CallbackPayload) SetComments(v string)`

SetComments sets Comments field to given value.

### HasComments

`func (o *CallbackPayload) HasComments() bool`

HasComments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



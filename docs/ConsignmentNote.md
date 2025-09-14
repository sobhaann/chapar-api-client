# ConsignmentNote

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tracking** | Pointer to **string** |  | [optional] 
**Date** | Pointer to **string** |  | [optional] 
**AssingedPieces** | Pointer to **string** |  | [optional] 
**Weight** | Pointer to **string** |  | [optional] 
**Service** | Pointer to **string** |  | [optional] 
**Value** | Pointer to **string** |  | [optional] 
**PaymentTerm** | Pointer to **string** |  | [optional] 
**LastStatus** | Pointer to **string** |  | [optional] 
**DeliveryDate** | Pointer to **string** |  | [optional] 
**DeliveryPerson** | Pointer to **string** |  | [optional] 
**ChangeStateUrl** | Pointer to **string** |  | [optional] 

## Methods

### NewConsignmentNote

`func NewConsignmentNote() *ConsignmentNote`

NewConsignmentNote instantiates a new ConsignmentNote object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConsignmentNoteWithDefaults

`func NewConsignmentNoteWithDefaults() *ConsignmentNote`

NewConsignmentNoteWithDefaults instantiates a new ConsignmentNote object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTracking

`func (o *ConsignmentNote) GetTracking() string`

GetTracking returns the Tracking field if non-nil, zero value otherwise.

### GetTrackingOk

`func (o *ConsignmentNote) GetTrackingOk() (*string, bool)`

GetTrackingOk returns a tuple with the Tracking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTracking

`func (o *ConsignmentNote) SetTracking(v string)`

SetTracking sets Tracking field to given value.

### HasTracking

`func (o *ConsignmentNote) HasTracking() bool`

HasTracking returns a boolean if a field has been set.

### GetDate

`func (o *ConsignmentNote) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ConsignmentNote) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ConsignmentNote) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *ConsignmentNote) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetAssingedPieces

`func (o *ConsignmentNote) GetAssingedPieces() string`

GetAssingedPieces returns the AssingedPieces field if non-nil, zero value otherwise.

### GetAssingedPiecesOk

`func (o *ConsignmentNote) GetAssingedPiecesOk() (*string, bool)`

GetAssingedPiecesOk returns a tuple with the AssingedPieces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssingedPieces

`func (o *ConsignmentNote) SetAssingedPieces(v string)`

SetAssingedPieces sets AssingedPieces field to given value.

### HasAssingedPieces

`func (o *ConsignmentNote) HasAssingedPieces() bool`

HasAssingedPieces returns a boolean if a field has been set.

### GetWeight

`func (o *ConsignmentNote) GetWeight() string`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *ConsignmentNote) GetWeightOk() (*string, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *ConsignmentNote) SetWeight(v string)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *ConsignmentNote) HasWeight() bool`

HasWeight returns a boolean if a field has been set.

### GetService

`func (o *ConsignmentNote) GetService() string`

GetService returns the Service field if non-nil, zero value otherwise.

### GetServiceOk

`func (o *ConsignmentNote) GetServiceOk() (*string, bool)`

GetServiceOk returns a tuple with the Service field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetService

`func (o *ConsignmentNote) SetService(v string)`

SetService sets Service field to given value.

### HasService

`func (o *ConsignmentNote) HasService() bool`

HasService returns a boolean if a field has been set.

### GetValue

`func (o *ConsignmentNote) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ConsignmentNote) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ConsignmentNote) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *ConsignmentNote) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetPaymentTerm

`func (o *ConsignmentNote) GetPaymentTerm() string`

GetPaymentTerm returns the PaymentTerm field if non-nil, zero value otherwise.

### GetPaymentTermOk

`func (o *ConsignmentNote) GetPaymentTermOk() (*string, bool)`

GetPaymentTermOk returns a tuple with the PaymentTerm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTerm

`func (o *ConsignmentNote) SetPaymentTerm(v string)`

SetPaymentTerm sets PaymentTerm field to given value.

### HasPaymentTerm

`func (o *ConsignmentNote) HasPaymentTerm() bool`

HasPaymentTerm returns a boolean if a field has been set.

### GetLastStatus

`func (o *ConsignmentNote) GetLastStatus() string`

GetLastStatus returns the LastStatus field if non-nil, zero value otherwise.

### GetLastStatusOk

`func (o *ConsignmentNote) GetLastStatusOk() (*string, bool)`

GetLastStatusOk returns a tuple with the LastStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastStatus

`func (o *ConsignmentNote) SetLastStatus(v string)`

SetLastStatus sets LastStatus field to given value.

### HasLastStatus

`func (o *ConsignmentNote) HasLastStatus() bool`

HasLastStatus returns a boolean if a field has been set.

### GetDeliveryDate

`func (o *ConsignmentNote) GetDeliveryDate() string`

GetDeliveryDate returns the DeliveryDate field if non-nil, zero value otherwise.

### GetDeliveryDateOk

`func (o *ConsignmentNote) GetDeliveryDateOk() (*string, bool)`

GetDeliveryDateOk returns a tuple with the DeliveryDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryDate

`func (o *ConsignmentNote) SetDeliveryDate(v string)`

SetDeliveryDate sets DeliveryDate field to given value.

### HasDeliveryDate

`func (o *ConsignmentNote) HasDeliveryDate() bool`

HasDeliveryDate returns a boolean if a field has been set.

### GetDeliveryPerson

`func (o *ConsignmentNote) GetDeliveryPerson() string`

GetDeliveryPerson returns the DeliveryPerson field if non-nil, zero value otherwise.

### GetDeliveryPersonOk

`func (o *ConsignmentNote) GetDeliveryPersonOk() (*string, bool)`

GetDeliveryPersonOk returns a tuple with the DeliveryPerson field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryPerson

`func (o *ConsignmentNote) SetDeliveryPerson(v string)`

SetDeliveryPerson sets DeliveryPerson field to given value.

### HasDeliveryPerson

`func (o *ConsignmentNote) HasDeliveryPerson() bool`

HasDeliveryPerson returns a boolean if a field has been set.

### GetChangeStateUrl

`func (o *ConsignmentNote) GetChangeStateUrl() string`

GetChangeStateUrl returns the ChangeStateUrl field if non-nil, zero value otherwise.

### GetChangeStateUrlOk

`func (o *ConsignmentNote) GetChangeStateUrlOk() (*string, bool)`

GetChangeStateUrlOk returns a tuple with the ChangeStateUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeStateUrl

`func (o *ConsignmentNote) SetChangeStateUrl(v string)`

SetChangeStateUrl sets ChangeStateUrl field to given value.

### HasChangeStateUrl

`func (o *ConsignmentNote) HasChangeStateUrl() bool`

HasChangeStateUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



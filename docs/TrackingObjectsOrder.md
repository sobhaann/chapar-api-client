# TrackingObjectsOrder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeliveredTo** | Pointer to **NullableString** |  | [optional] 
**DeliveryTime** | Pointer to **NullableString** |  | [optional] 
**Signature** | Pointer to **NullableString** |  | [optional] 
**Geo** | Pointer to [**TrackingObjectsOrderGeo**](TrackingObjectsOrderGeo.md) |  | [optional] 
**History** | Pointer to [**[]TrackingHistoryItem**](TrackingHistoryItem.md) |  | [optional] 
**Origin** | Pointer to **NullableString** |  | [optional] 
**Dest** | Pointer to **NullableString** |  | [optional] 
**PickupAgentCode** | Pointer to **NullableString** |  | [optional] 
**PickupAgent** | Pointer to **NullableString** |  | [optional] 
**PickupAgentPhone** | Pointer to **NullableString** |  | [optional] 
**DeliveryAgentCode** | Pointer to **NullableString** |  | [optional] 
**DeliveryAgent** | Pointer to **NullableString** |  | [optional] 
**DeliveryAgentPhone** | Pointer to **NullableString** |  | [optional] 
**SenderCode** | Pointer to **NullableString** |  | [optional] 
**SenderCompany** | Pointer to **NullableString** |  | [optional] 
**SenderContact** | Pointer to **NullableString** |  | [optional] 
**SenderPhone** | Pointer to **NullableString** |  | [optional] 
**ReceiverCompany** | Pointer to **NullableString** |  | [optional] 
**ReceiverContact** | Pointer to **NullableString** |  | [optional] 
**ReceiverPhone** | Pointer to **NullableString** |  | [optional] 
**ThirdReference** | Pointer to **NullableString** |  | [optional] 
**Method** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTrackingObjectsOrder

`func NewTrackingObjectsOrder() *TrackingObjectsOrder`

NewTrackingObjectsOrder instantiates a new TrackingObjectsOrder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackingObjectsOrderWithDefaults

`func NewTrackingObjectsOrderWithDefaults() *TrackingObjectsOrder`

NewTrackingObjectsOrderWithDefaults instantiates a new TrackingObjectsOrder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliveredTo

`func (o *TrackingObjectsOrder) GetDeliveredTo() string`

GetDeliveredTo returns the DeliveredTo field if non-nil, zero value otherwise.

### GetDeliveredToOk

`func (o *TrackingObjectsOrder) GetDeliveredToOk() (*string, bool)`

GetDeliveredToOk returns a tuple with the DeliveredTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveredTo

`func (o *TrackingObjectsOrder) SetDeliveredTo(v string)`

SetDeliveredTo sets DeliveredTo field to given value.

### HasDeliveredTo

`func (o *TrackingObjectsOrder) HasDeliveredTo() bool`

HasDeliveredTo returns a boolean if a field has been set.

### SetDeliveredToNil

`func (o *TrackingObjectsOrder) SetDeliveredToNil(b bool)`

 SetDeliveredToNil sets the value for DeliveredTo to be an explicit nil

### UnsetDeliveredTo
`func (o *TrackingObjectsOrder) UnsetDeliveredTo()`

UnsetDeliveredTo ensures that no value is present for DeliveredTo, not even an explicit nil
### GetDeliveryTime

`func (o *TrackingObjectsOrder) GetDeliveryTime() string`

GetDeliveryTime returns the DeliveryTime field if non-nil, zero value otherwise.

### GetDeliveryTimeOk

`func (o *TrackingObjectsOrder) GetDeliveryTimeOk() (*string, bool)`

GetDeliveryTimeOk returns a tuple with the DeliveryTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryTime

`func (o *TrackingObjectsOrder) SetDeliveryTime(v string)`

SetDeliveryTime sets DeliveryTime field to given value.

### HasDeliveryTime

`func (o *TrackingObjectsOrder) HasDeliveryTime() bool`

HasDeliveryTime returns a boolean if a field has been set.

### SetDeliveryTimeNil

`func (o *TrackingObjectsOrder) SetDeliveryTimeNil(b bool)`

 SetDeliveryTimeNil sets the value for DeliveryTime to be an explicit nil

### UnsetDeliveryTime
`func (o *TrackingObjectsOrder) UnsetDeliveryTime()`

UnsetDeliveryTime ensures that no value is present for DeliveryTime, not even an explicit nil
### GetSignature

`func (o *TrackingObjectsOrder) GetSignature() string`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *TrackingObjectsOrder) GetSignatureOk() (*string, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *TrackingObjectsOrder) SetSignature(v string)`

SetSignature sets Signature field to given value.

### HasSignature

`func (o *TrackingObjectsOrder) HasSignature() bool`

HasSignature returns a boolean if a field has been set.

### SetSignatureNil

`func (o *TrackingObjectsOrder) SetSignatureNil(b bool)`

 SetSignatureNil sets the value for Signature to be an explicit nil

### UnsetSignature
`func (o *TrackingObjectsOrder) UnsetSignature()`

UnsetSignature ensures that no value is present for Signature, not even an explicit nil
### GetGeo

`func (o *TrackingObjectsOrder) GetGeo() TrackingObjectsOrderGeo`

GetGeo returns the Geo field if non-nil, zero value otherwise.

### GetGeoOk

`func (o *TrackingObjectsOrder) GetGeoOk() (*TrackingObjectsOrderGeo, bool)`

GetGeoOk returns a tuple with the Geo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeo

`func (o *TrackingObjectsOrder) SetGeo(v TrackingObjectsOrderGeo)`

SetGeo sets Geo field to given value.

### HasGeo

`func (o *TrackingObjectsOrder) HasGeo() bool`

HasGeo returns a boolean if a field has been set.

### GetHistory

`func (o *TrackingObjectsOrder) GetHistory() []TrackingHistoryItem`

GetHistory returns the History field if non-nil, zero value otherwise.

### GetHistoryOk

`func (o *TrackingObjectsOrder) GetHistoryOk() (*[]TrackingHistoryItem, bool)`

GetHistoryOk returns a tuple with the History field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistory

`func (o *TrackingObjectsOrder) SetHistory(v []TrackingHistoryItem)`

SetHistory sets History field to given value.

### HasHistory

`func (o *TrackingObjectsOrder) HasHistory() bool`

HasHistory returns a boolean if a field has been set.

### GetOrigin

`func (o *TrackingObjectsOrder) GetOrigin() string`

GetOrigin returns the Origin field if non-nil, zero value otherwise.

### GetOriginOk

`func (o *TrackingObjectsOrder) GetOriginOk() (*string, bool)`

GetOriginOk returns a tuple with the Origin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrigin

`func (o *TrackingObjectsOrder) SetOrigin(v string)`

SetOrigin sets Origin field to given value.

### HasOrigin

`func (o *TrackingObjectsOrder) HasOrigin() bool`

HasOrigin returns a boolean if a field has been set.

### SetOriginNil

`func (o *TrackingObjectsOrder) SetOriginNil(b bool)`

 SetOriginNil sets the value for Origin to be an explicit nil

### UnsetOrigin
`func (o *TrackingObjectsOrder) UnsetOrigin()`

UnsetOrigin ensures that no value is present for Origin, not even an explicit nil
### GetDest

`func (o *TrackingObjectsOrder) GetDest() string`

GetDest returns the Dest field if non-nil, zero value otherwise.

### GetDestOk

`func (o *TrackingObjectsOrder) GetDestOk() (*string, bool)`

GetDestOk returns a tuple with the Dest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDest

`func (o *TrackingObjectsOrder) SetDest(v string)`

SetDest sets Dest field to given value.

### HasDest

`func (o *TrackingObjectsOrder) HasDest() bool`

HasDest returns a boolean if a field has been set.

### SetDestNil

`func (o *TrackingObjectsOrder) SetDestNil(b bool)`

 SetDestNil sets the value for Dest to be an explicit nil

### UnsetDest
`func (o *TrackingObjectsOrder) UnsetDest()`

UnsetDest ensures that no value is present for Dest, not even an explicit nil
### GetPickupAgentCode

`func (o *TrackingObjectsOrder) GetPickupAgentCode() string`

GetPickupAgentCode returns the PickupAgentCode field if non-nil, zero value otherwise.

### GetPickupAgentCodeOk

`func (o *TrackingObjectsOrder) GetPickupAgentCodeOk() (*string, bool)`

GetPickupAgentCodeOk returns a tuple with the PickupAgentCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickupAgentCode

`func (o *TrackingObjectsOrder) SetPickupAgentCode(v string)`

SetPickupAgentCode sets PickupAgentCode field to given value.

### HasPickupAgentCode

`func (o *TrackingObjectsOrder) HasPickupAgentCode() bool`

HasPickupAgentCode returns a boolean if a field has been set.

### SetPickupAgentCodeNil

`func (o *TrackingObjectsOrder) SetPickupAgentCodeNil(b bool)`

 SetPickupAgentCodeNil sets the value for PickupAgentCode to be an explicit nil

### UnsetPickupAgentCode
`func (o *TrackingObjectsOrder) UnsetPickupAgentCode()`

UnsetPickupAgentCode ensures that no value is present for PickupAgentCode, not even an explicit nil
### GetPickupAgent

`func (o *TrackingObjectsOrder) GetPickupAgent() string`

GetPickupAgent returns the PickupAgent field if non-nil, zero value otherwise.

### GetPickupAgentOk

`func (o *TrackingObjectsOrder) GetPickupAgentOk() (*string, bool)`

GetPickupAgentOk returns a tuple with the PickupAgent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickupAgent

`func (o *TrackingObjectsOrder) SetPickupAgent(v string)`

SetPickupAgent sets PickupAgent field to given value.

### HasPickupAgent

`func (o *TrackingObjectsOrder) HasPickupAgent() bool`

HasPickupAgent returns a boolean if a field has been set.

### SetPickupAgentNil

`func (o *TrackingObjectsOrder) SetPickupAgentNil(b bool)`

 SetPickupAgentNil sets the value for PickupAgent to be an explicit nil

### UnsetPickupAgent
`func (o *TrackingObjectsOrder) UnsetPickupAgent()`

UnsetPickupAgent ensures that no value is present for PickupAgent, not even an explicit nil
### GetPickupAgentPhone

`func (o *TrackingObjectsOrder) GetPickupAgentPhone() string`

GetPickupAgentPhone returns the PickupAgentPhone field if non-nil, zero value otherwise.

### GetPickupAgentPhoneOk

`func (o *TrackingObjectsOrder) GetPickupAgentPhoneOk() (*string, bool)`

GetPickupAgentPhoneOk returns a tuple with the PickupAgentPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickupAgentPhone

`func (o *TrackingObjectsOrder) SetPickupAgentPhone(v string)`

SetPickupAgentPhone sets PickupAgentPhone field to given value.

### HasPickupAgentPhone

`func (o *TrackingObjectsOrder) HasPickupAgentPhone() bool`

HasPickupAgentPhone returns a boolean if a field has been set.

### SetPickupAgentPhoneNil

`func (o *TrackingObjectsOrder) SetPickupAgentPhoneNil(b bool)`

 SetPickupAgentPhoneNil sets the value for PickupAgentPhone to be an explicit nil

### UnsetPickupAgentPhone
`func (o *TrackingObjectsOrder) UnsetPickupAgentPhone()`

UnsetPickupAgentPhone ensures that no value is present for PickupAgentPhone, not even an explicit nil
### GetDeliveryAgentCode

`func (o *TrackingObjectsOrder) GetDeliveryAgentCode() string`

GetDeliveryAgentCode returns the DeliveryAgentCode field if non-nil, zero value otherwise.

### GetDeliveryAgentCodeOk

`func (o *TrackingObjectsOrder) GetDeliveryAgentCodeOk() (*string, bool)`

GetDeliveryAgentCodeOk returns a tuple with the DeliveryAgentCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryAgentCode

`func (o *TrackingObjectsOrder) SetDeliveryAgentCode(v string)`

SetDeliveryAgentCode sets DeliveryAgentCode field to given value.

### HasDeliveryAgentCode

`func (o *TrackingObjectsOrder) HasDeliveryAgentCode() bool`

HasDeliveryAgentCode returns a boolean if a field has been set.

### SetDeliveryAgentCodeNil

`func (o *TrackingObjectsOrder) SetDeliveryAgentCodeNil(b bool)`

 SetDeliveryAgentCodeNil sets the value for DeliveryAgentCode to be an explicit nil

### UnsetDeliveryAgentCode
`func (o *TrackingObjectsOrder) UnsetDeliveryAgentCode()`

UnsetDeliveryAgentCode ensures that no value is present for DeliveryAgentCode, not even an explicit nil
### GetDeliveryAgent

`func (o *TrackingObjectsOrder) GetDeliveryAgent() string`

GetDeliveryAgent returns the DeliveryAgent field if non-nil, zero value otherwise.

### GetDeliveryAgentOk

`func (o *TrackingObjectsOrder) GetDeliveryAgentOk() (*string, bool)`

GetDeliveryAgentOk returns a tuple with the DeliveryAgent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryAgent

`func (o *TrackingObjectsOrder) SetDeliveryAgent(v string)`

SetDeliveryAgent sets DeliveryAgent field to given value.

### HasDeliveryAgent

`func (o *TrackingObjectsOrder) HasDeliveryAgent() bool`

HasDeliveryAgent returns a boolean if a field has been set.

### SetDeliveryAgentNil

`func (o *TrackingObjectsOrder) SetDeliveryAgentNil(b bool)`

 SetDeliveryAgentNil sets the value for DeliveryAgent to be an explicit nil

### UnsetDeliveryAgent
`func (o *TrackingObjectsOrder) UnsetDeliveryAgent()`

UnsetDeliveryAgent ensures that no value is present for DeliveryAgent, not even an explicit nil
### GetDeliveryAgentPhone

`func (o *TrackingObjectsOrder) GetDeliveryAgentPhone() string`

GetDeliveryAgentPhone returns the DeliveryAgentPhone field if non-nil, zero value otherwise.

### GetDeliveryAgentPhoneOk

`func (o *TrackingObjectsOrder) GetDeliveryAgentPhoneOk() (*string, bool)`

GetDeliveryAgentPhoneOk returns a tuple with the DeliveryAgentPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryAgentPhone

`func (o *TrackingObjectsOrder) SetDeliveryAgentPhone(v string)`

SetDeliveryAgentPhone sets DeliveryAgentPhone field to given value.

### HasDeliveryAgentPhone

`func (o *TrackingObjectsOrder) HasDeliveryAgentPhone() bool`

HasDeliveryAgentPhone returns a boolean if a field has been set.

### SetDeliveryAgentPhoneNil

`func (o *TrackingObjectsOrder) SetDeliveryAgentPhoneNil(b bool)`

 SetDeliveryAgentPhoneNil sets the value for DeliveryAgentPhone to be an explicit nil

### UnsetDeliveryAgentPhone
`func (o *TrackingObjectsOrder) UnsetDeliveryAgentPhone()`

UnsetDeliveryAgentPhone ensures that no value is present for DeliveryAgentPhone, not even an explicit nil
### GetSenderCode

`func (o *TrackingObjectsOrder) GetSenderCode() string`

GetSenderCode returns the SenderCode field if non-nil, zero value otherwise.

### GetSenderCodeOk

`func (o *TrackingObjectsOrder) GetSenderCodeOk() (*string, bool)`

GetSenderCodeOk returns a tuple with the SenderCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderCode

`func (o *TrackingObjectsOrder) SetSenderCode(v string)`

SetSenderCode sets SenderCode field to given value.

### HasSenderCode

`func (o *TrackingObjectsOrder) HasSenderCode() bool`

HasSenderCode returns a boolean if a field has been set.

### SetSenderCodeNil

`func (o *TrackingObjectsOrder) SetSenderCodeNil(b bool)`

 SetSenderCodeNil sets the value for SenderCode to be an explicit nil

### UnsetSenderCode
`func (o *TrackingObjectsOrder) UnsetSenderCode()`

UnsetSenderCode ensures that no value is present for SenderCode, not even an explicit nil
### GetSenderCompany

`func (o *TrackingObjectsOrder) GetSenderCompany() string`

GetSenderCompany returns the SenderCompany field if non-nil, zero value otherwise.

### GetSenderCompanyOk

`func (o *TrackingObjectsOrder) GetSenderCompanyOk() (*string, bool)`

GetSenderCompanyOk returns a tuple with the SenderCompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderCompany

`func (o *TrackingObjectsOrder) SetSenderCompany(v string)`

SetSenderCompany sets SenderCompany field to given value.

### HasSenderCompany

`func (o *TrackingObjectsOrder) HasSenderCompany() bool`

HasSenderCompany returns a boolean if a field has been set.

### SetSenderCompanyNil

`func (o *TrackingObjectsOrder) SetSenderCompanyNil(b bool)`

 SetSenderCompanyNil sets the value for SenderCompany to be an explicit nil

### UnsetSenderCompany
`func (o *TrackingObjectsOrder) UnsetSenderCompany()`

UnsetSenderCompany ensures that no value is present for SenderCompany, not even an explicit nil
### GetSenderContact

`func (o *TrackingObjectsOrder) GetSenderContact() string`

GetSenderContact returns the SenderContact field if non-nil, zero value otherwise.

### GetSenderContactOk

`func (o *TrackingObjectsOrder) GetSenderContactOk() (*string, bool)`

GetSenderContactOk returns a tuple with the SenderContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderContact

`func (o *TrackingObjectsOrder) SetSenderContact(v string)`

SetSenderContact sets SenderContact field to given value.

### HasSenderContact

`func (o *TrackingObjectsOrder) HasSenderContact() bool`

HasSenderContact returns a boolean if a field has been set.

### SetSenderContactNil

`func (o *TrackingObjectsOrder) SetSenderContactNil(b bool)`

 SetSenderContactNil sets the value for SenderContact to be an explicit nil

### UnsetSenderContact
`func (o *TrackingObjectsOrder) UnsetSenderContact()`

UnsetSenderContact ensures that no value is present for SenderContact, not even an explicit nil
### GetSenderPhone

`func (o *TrackingObjectsOrder) GetSenderPhone() string`

GetSenderPhone returns the SenderPhone field if non-nil, zero value otherwise.

### GetSenderPhoneOk

`func (o *TrackingObjectsOrder) GetSenderPhoneOk() (*string, bool)`

GetSenderPhoneOk returns a tuple with the SenderPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderPhone

`func (o *TrackingObjectsOrder) SetSenderPhone(v string)`

SetSenderPhone sets SenderPhone field to given value.

### HasSenderPhone

`func (o *TrackingObjectsOrder) HasSenderPhone() bool`

HasSenderPhone returns a boolean if a field has been set.

### SetSenderPhoneNil

`func (o *TrackingObjectsOrder) SetSenderPhoneNil(b bool)`

 SetSenderPhoneNil sets the value for SenderPhone to be an explicit nil

### UnsetSenderPhone
`func (o *TrackingObjectsOrder) UnsetSenderPhone()`

UnsetSenderPhone ensures that no value is present for SenderPhone, not even an explicit nil
### GetReceiverCompany

`func (o *TrackingObjectsOrder) GetReceiverCompany() string`

GetReceiverCompany returns the ReceiverCompany field if non-nil, zero value otherwise.

### GetReceiverCompanyOk

`func (o *TrackingObjectsOrder) GetReceiverCompanyOk() (*string, bool)`

GetReceiverCompanyOk returns a tuple with the ReceiverCompany field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiverCompany

`func (o *TrackingObjectsOrder) SetReceiverCompany(v string)`

SetReceiverCompany sets ReceiverCompany field to given value.

### HasReceiverCompany

`func (o *TrackingObjectsOrder) HasReceiverCompany() bool`

HasReceiverCompany returns a boolean if a field has been set.

### SetReceiverCompanyNil

`func (o *TrackingObjectsOrder) SetReceiverCompanyNil(b bool)`

 SetReceiverCompanyNil sets the value for ReceiverCompany to be an explicit nil

### UnsetReceiverCompany
`func (o *TrackingObjectsOrder) UnsetReceiverCompany()`

UnsetReceiverCompany ensures that no value is present for ReceiverCompany, not even an explicit nil
### GetReceiverContact

`func (o *TrackingObjectsOrder) GetReceiverContact() string`

GetReceiverContact returns the ReceiverContact field if non-nil, zero value otherwise.

### GetReceiverContactOk

`func (o *TrackingObjectsOrder) GetReceiverContactOk() (*string, bool)`

GetReceiverContactOk returns a tuple with the ReceiverContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiverContact

`func (o *TrackingObjectsOrder) SetReceiverContact(v string)`

SetReceiverContact sets ReceiverContact field to given value.

### HasReceiverContact

`func (o *TrackingObjectsOrder) HasReceiverContact() bool`

HasReceiverContact returns a boolean if a field has been set.

### SetReceiverContactNil

`func (o *TrackingObjectsOrder) SetReceiverContactNil(b bool)`

 SetReceiverContactNil sets the value for ReceiverContact to be an explicit nil

### UnsetReceiverContact
`func (o *TrackingObjectsOrder) UnsetReceiverContact()`

UnsetReceiverContact ensures that no value is present for ReceiverContact, not even an explicit nil
### GetReceiverPhone

`func (o *TrackingObjectsOrder) GetReceiverPhone() string`

GetReceiverPhone returns the ReceiverPhone field if non-nil, zero value otherwise.

### GetReceiverPhoneOk

`func (o *TrackingObjectsOrder) GetReceiverPhoneOk() (*string, bool)`

GetReceiverPhoneOk returns a tuple with the ReceiverPhone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiverPhone

`func (o *TrackingObjectsOrder) SetReceiverPhone(v string)`

SetReceiverPhone sets ReceiverPhone field to given value.

### HasReceiverPhone

`func (o *TrackingObjectsOrder) HasReceiverPhone() bool`

HasReceiverPhone returns a boolean if a field has been set.

### SetReceiverPhoneNil

`func (o *TrackingObjectsOrder) SetReceiverPhoneNil(b bool)`

 SetReceiverPhoneNil sets the value for ReceiverPhone to be an explicit nil

### UnsetReceiverPhone
`func (o *TrackingObjectsOrder) UnsetReceiverPhone()`

UnsetReceiverPhone ensures that no value is present for ReceiverPhone, not even an explicit nil
### GetThirdReference

`func (o *TrackingObjectsOrder) GetThirdReference() string`

GetThirdReference returns the ThirdReference field if non-nil, zero value otherwise.

### GetThirdReferenceOk

`func (o *TrackingObjectsOrder) GetThirdReferenceOk() (*string, bool)`

GetThirdReferenceOk returns a tuple with the ThirdReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdReference

`func (o *TrackingObjectsOrder) SetThirdReference(v string)`

SetThirdReference sets ThirdReference field to given value.

### HasThirdReference

`func (o *TrackingObjectsOrder) HasThirdReference() bool`

HasThirdReference returns a boolean if a field has been set.

### SetThirdReferenceNil

`func (o *TrackingObjectsOrder) SetThirdReferenceNil(b bool)`

 SetThirdReferenceNil sets the value for ThirdReference to be an explicit nil

### UnsetThirdReference
`func (o *TrackingObjectsOrder) UnsetThirdReference()`

UnsetThirdReference ensures that no value is present for ThirdReference, not even an explicit nil
### GetMethod

`func (o *TrackingObjectsOrder) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *TrackingObjectsOrder) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *TrackingObjectsOrder) SetMethod(v string)`

SetMethod sets Method field to given value.

### HasMethod

`func (o *TrackingObjectsOrder) HasMethod() bool`

HasMethod returns a boolean if a field has been set.

### SetMethodNil

`func (o *TrackingObjectsOrder) SetMethodNil(b bool)`

 SetMethodNil sets the value for Method to be an explicit nil

### UnsetMethod
`func (o *TrackingObjectsOrder) UnsetMethod()`

UnsetMethod ensures that no value is present for Method, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



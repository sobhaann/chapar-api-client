# PriceDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Zone** | **string** |  | 
**FldManualCost** | **int32** |  | 
**FldPackCost** | Pointer to **int32** |  | [optional] 
**FldChargeCost** | Pointer to **int32** |  | [optional] 
**FldManualInsurance** | Pointer to **int32** |  | [optional] 
**FldLabCost** | Pointer to **int32** |  | [optional] 
**FldManualVAT** | Pointer to **int32** |  | [optional] 
**FldTotalCost** | **int32** |  | 
**PriceList** | Pointer to **string** |  | [optional] 
**MinIns** | Pointer to **string** |  | [optional] 

## Methods

### NewPriceDetails

`func NewPriceDetails(zone string, fldManualCost int32, fldTotalCost int32, ) *PriceDetails`

NewPriceDetails instantiates a new PriceDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceDetailsWithDefaults

`func NewPriceDetailsWithDefaults() *PriceDetails`

NewPriceDetailsWithDefaults instantiates a new PriceDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetZone

`func (o *PriceDetails) GetZone() string`

GetZone returns the Zone field if non-nil, zero value otherwise.

### GetZoneOk

`func (o *PriceDetails) GetZoneOk() (*string, bool)`

GetZoneOk returns a tuple with the Zone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZone

`func (o *PriceDetails) SetZone(v string)`

SetZone sets Zone field to given value.


### GetFldManualCost

`func (o *PriceDetails) GetFldManualCost() int32`

GetFldManualCost returns the FldManualCost field if non-nil, zero value otherwise.

### GetFldManualCostOk

`func (o *PriceDetails) GetFldManualCostOk() (*int32, bool)`

GetFldManualCostOk returns a tuple with the FldManualCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldManualCost

`func (o *PriceDetails) SetFldManualCost(v int32)`

SetFldManualCost sets FldManualCost field to given value.


### GetFldPackCost

`func (o *PriceDetails) GetFldPackCost() int32`

GetFldPackCost returns the FldPackCost field if non-nil, zero value otherwise.

### GetFldPackCostOk

`func (o *PriceDetails) GetFldPackCostOk() (*int32, bool)`

GetFldPackCostOk returns a tuple with the FldPackCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldPackCost

`func (o *PriceDetails) SetFldPackCost(v int32)`

SetFldPackCost sets FldPackCost field to given value.

### HasFldPackCost

`func (o *PriceDetails) HasFldPackCost() bool`

HasFldPackCost returns a boolean if a field has been set.

### GetFldChargeCost

`func (o *PriceDetails) GetFldChargeCost() int32`

GetFldChargeCost returns the FldChargeCost field if non-nil, zero value otherwise.

### GetFldChargeCostOk

`func (o *PriceDetails) GetFldChargeCostOk() (*int32, bool)`

GetFldChargeCostOk returns a tuple with the FldChargeCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldChargeCost

`func (o *PriceDetails) SetFldChargeCost(v int32)`

SetFldChargeCost sets FldChargeCost field to given value.

### HasFldChargeCost

`func (o *PriceDetails) HasFldChargeCost() bool`

HasFldChargeCost returns a boolean if a field has been set.

### GetFldManualInsurance

`func (o *PriceDetails) GetFldManualInsurance() int32`

GetFldManualInsurance returns the FldManualInsurance field if non-nil, zero value otherwise.

### GetFldManualInsuranceOk

`func (o *PriceDetails) GetFldManualInsuranceOk() (*int32, bool)`

GetFldManualInsuranceOk returns a tuple with the FldManualInsurance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldManualInsurance

`func (o *PriceDetails) SetFldManualInsurance(v int32)`

SetFldManualInsurance sets FldManualInsurance field to given value.

### HasFldManualInsurance

`func (o *PriceDetails) HasFldManualInsurance() bool`

HasFldManualInsurance returns a boolean if a field has been set.

### GetFldLabCost

`func (o *PriceDetails) GetFldLabCost() int32`

GetFldLabCost returns the FldLabCost field if non-nil, zero value otherwise.

### GetFldLabCostOk

`func (o *PriceDetails) GetFldLabCostOk() (*int32, bool)`

GetFldLabCostOk returns a tuple with the FldLabCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldLabCost

`func (o *PriceDetails) SetFldLabCost(v int32)`

SetFldLabCost sets FldLabCost field to given value.

### HasFldLabCost

`func (o *PriceDetails) HasFldLabCost() bool`

HasFldLabCost returns a boolean if a field has been set.

### GetFldManualVAT

`func (o *PriceDetails) GetFldManualVAT() int32`

GetFldManualVAT returns the FldManualVAT field if non-nil, zero value otherwise.

### GetFldManualVATOk

`func (o *PriceDetails) GetFldManualVATOk() (*int32, bool)`

GetFldManualVATOk returns a tuple with the FldManualVAT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldManualVAT

`func (o *PriceDetails) SetFldManualVAT(v int32)`

SetFldManualVAT sets FldManualVAT field to given value.

### HasFldManualVAT

`func (o *PriceDetails) HasFldManualVAT() bool`

HasFldManualVAT returns a boolean if a field has been set.

### GetFldTotalCost

`func (o *PriceDetails) GetFldTotalCost() int32`

GetFldTotalCost returns the FldTotalCost field if non-nil, zero value otherwise.

### GetFldTotalCostOk

`func (o *PriceDetails) GetFldTotalCostOk() (*int32, bool)`

GetFldTotalCostOk returns a tuple with the FldTotalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldTotalCost

`func (o *PriceDetails) SetFldTotalCost(v int32)`

SetFldTotalCost sets FldTotalCost field to given value.


### GetPriceList

`func (o *PriceDetails) GetPriceList() string`

GetPriceList returns the PriceList field if non-nil, zero value otherwise.

### GetPriceListOk

`func (o *PriceDetails) GetPriceListOk() (*string, bool)`

GetPriceListOk returns a tuple with the PriceList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceList

`func (o *PriceDetails) SetPriceList(v string)`

SetPriceList sets PriceList field to given value.

### HasPriceList

`func (o *PriceDetails) HasPriceList() bool`

HasPriceList returns a boolean if a field has been set.

### GetMinIns

`func (o *PriceDetails) GetMinIns() string`

GetMinIns returns the MinIns field if non-nil, zero value otherwise.

### GetMinInsOk

`func (o *PriceDetails) GetMinInsOk() (*string, bool)`

GetMinInsOk returns a tuple with the MinIns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinIns

`func (o *PriceDetails) SetMinIns(v string)`

SetMinIns sets MinIns field to given value.

### HasMinIns

`func (o *PriceDetails) HasMinIns() bool`

HasMinIns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



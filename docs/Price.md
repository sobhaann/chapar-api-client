# Price

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Zone** | Pointer to **string** |  | [optional] 
**FldManualCost** | Pointer to **int32** |  | [optional] 
**FldPackCost** | Pointer to **int32** |  | [optional] 
**FldChargeCost** | Pointer to **int32** |  | [optional] 
**FldManualInsurance** | Pointer to **int32** |  | [optional] 
**FldLabCost** | Pointer to **int32** |  | [optional] 
**FldManualVAT** | Pointer to **int32** |  | [optional] 
**FldTotalCost** | Pointer to **int32** |  | [optional] 
**PriceList** | Pointer to **string** |  | [optional] 
**MinIns** | Pointer to **string** |  | [optional] 

## Methods

### NewPrice

`func NewPrice() *Price`

NewPrice instantiates a new Price object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceWithDefaults

`func NewPriceWithDefaults() *Price`

NewPriceWithDefaults instantiates a new Price object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetZone

`func (o *Price) GetZone() string`

GetZone returns the Zone field if non-nil, zero value otherwise.

### GetZoneOk

`func (o *Price) GetZoneOk() (*string, bool)`

GetZoneOk returns a tuple with the Zone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZone

`func (o *Price) SetZone(v string)`

SetZone sets Zone field to given value.

### HasZone

`func (o *Price) HasZone() bool`

HasZone returns a boolean if a field has been set.

### GetFldManualCost

`func (o *Price) GetFldManualCost() int32`

GetFldManualCost returns the FldManualCost field if non-nil, zero value otherwise.

### GetFldManualCostOk

`func (o *Price) GetFldManualCostOk() (*int32, bool)`

GetFldManualCostOk returns a tuple with the FldManualCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldManualCost

`func (o *Price) SetFldManualCost(v int32)`

SetFldManualCost sets FldManualCost field to given value.

### HasFldManualCost

`func (o *Price) HasFldManualCost() bool`

HasFldManualCost returns a boolean if a field has been set.

### GetFldPackCost

`func (o *Price) GetFldPackCost() int32`

GetFldPackCost returns the FldPackCost field if non-nil, zero value otherwise.

### GetFldPackCostOk

`func (o *Price) GetFldPackCostOk() (*int32, bool)`

GetFldPackCostOk returns a tuple with the FldPackCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldPackCost

`func (o *Price) SetFldPackCost(v int32)`

SetFldPackCost sets FldPackCost field to given value.

### HasFldPackCost

`func (o *Price) HasFldPackCost() bool`

HasFldPackCost returns a boolean if a field has been set.

### GetFldChargeCost

`func (o *Price) GetFldChargeCost() int32`

GetFldChargeCost returns the FldChargeCost field if non-nil, zero value otherwise.

### GetFldChargeCostOk

`func (o *Price) GetFldChargeCostOk() (*int32, bool)`

GetFldChargeCostOk returns a tuple with the FldChargeCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldChargeCost

`func (o *Price) SetFldChargeCost(v int32)`

SetFldChargeCost sets FldChargeCost field to given value.

### HasFldChargeCost

`func (o *Price) HasFldChargeCost() bool`

HasFldChargeCost returns a boolean if a field has been set.

### GetFldManualInsurance

`func (o *Price) GetFldManualInsurance() int32`

GetFldManualInsurance returns the FldManualInsurance field if non-nil, zero value otherwise.

### GetFldManualInsuranceOk

`func (o *Price) GetFldManualInsuranceOk() (*int32, bool)`

GetFldManualInsuranceOk returns a tuple with the FldManualInsurance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldManualInsurance

`func (o *Price) SetFldManualInsurance(v int32)`

SetFldManualInsurance sets FldManualInsurance field to given value.

### HasFldManualInsurance

`func (o *Price) HasFldManualInsurance() bool`

HasFldManualInsurance returns a boolean if a field has been set.

### GetFldLabCost

`func (o *Price) GetFldLabCost() int32`

GetFldLabCost returns the FldLabCost field if non-nil, zero value otherwise.

### GetFldLabCostOk

`func (o *Price) GetFldLabCostOk() (*int32, bool)`

GetFldLabCostOk returns a tuple with the FldLabCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldLabCost

`func (o *Price) SetFldLabCost(v int32)`

SetFldLabCost sets FldLabCost field to given value.

### HasFldLabCost

`func (o *Price) HasFldLabCost() bool`

HasFldLabCost returns a boolean if a field has been set.

### GetFldManualVAT

`func (o *Price) GetFldManualVAT() int32`

GetFldManualVAT returns the FldManualVAT field if non-nil, zero value otherwise.

### GetFldManualVATOk

`func (o *Price) GetFldManualVATOk() (*int32, bool)`

GetFldManualVATOk returns a tuple with the FldManualVAT field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldManualVAT

`func (o *Price) SetFldManualVAT(v int32)`

SetFldManualVAT sets FldManualVAT field to given value.

### HasFldManualVAT

`func (o *Price) HasFldManualVAT() bool`

HasFldManualVAT returns a boolean if a field has been set.

### GetFldTotalCost

`func (o *Price) GetFldTotalCost() int32`

GetFldTotalCost returns the FldTotalCost field if non-nil, zero value otherwise.

### GetFldTotalCostOk

`func (o *Price) GetFldTotalCostOk() (*int32, bool)`

GetFldTotalCostOk returns a tuple with the FldTotalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFldTotalCost

`func (o *Price) SetFldTotalCost(v int32)`

SetFldTotalCost sets FldTotalCost field to given value.

### HasFldTotalCost

`func (o *Price) HasFldTotalCost() bool`

HasFldTotalCost returns a boolean if a field has been set.

### GetPriceList

`func (o *Price) GetPriceList() string`

GetPriceList returns the PriceList field if non-nil, zero value otherwise.

### GetPriceListOk

`func (o *Price) GetPriceListOk() (*string, bool)`

GetPriceListOk returns a tuple with the PriceList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceList

`func (o *Price) SetPriceList(v string)`

SetPriceList sets PriceList field to given value.

### HasPriceList

`func (o *Price) HasPriceList() bool`

HasPriceList returns a boolean if a field has been set.

### GetMinIns

`func (o *Price) GetMinIns() string`

GetMinIns returns the MinIns field if non-nil, zero value otherwise.

### GetMinInsOk

`func (o *Price) GetMinInsOk() (*string, bool)`

GetMinInsOk returns a tuple with the MinIns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinIns

`func (o *Price) SetMinIns(v string)`

SetMinIns sets MinIns field to given value.

### HasMinIns

`func (o *Price) HasMinIns() bool`

HasMinIns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



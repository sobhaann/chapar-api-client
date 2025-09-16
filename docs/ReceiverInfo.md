# ReceiverInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Person** | **string** |  | 
**Company** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewReceiverInfo

`func NewReceiverInfo(person string, ) *ReceiverInfo`

NewReceiverInfo instantiates a new ReceiverInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiverInfoWithDefaults

`func NewReceiverInfoWithDefaults() *ReceiverInfo`

NewReceiverInfoWithDefaults instantiates a new ReceiverInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPerson

`func (o *ReceiverInfo) GetPerson() string`

GetPerson returns the Person field if non-nil, zero value otherwise.

### GetPersonOk

`func (o *ReceiverInfo) GetPersonOk() (*string, bool)`

GetPersonOk returns a tuple with the Person field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerson

`func (o *ReceiverInfo) SetPerson(v string)`

SetPerson sets Person field to given value.


### GetCompany

`func (o *ReceiverInfo) GetCompany() string`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *ReceiverInfo) GetCompanyOk() (*string, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *ReceiverInfo) SetCompany(v string)`

SetCompany sets Company field to given value.

### HasCompany

`func (o *ReceiverInfo) HasCompany() bool`

HasCompany returns a boolean if a field has been set.

### SetCompanyNil

`func (o *ReceiverInfo) SetCompanyNil(b bool)`

 SetCompanyNil sets the value for Company to be an explicit nil

### UnsetCompany
`func (o *ReceiverInfo) UnsetCompany()`

UnsetCompany ensures that no value is present for Company, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



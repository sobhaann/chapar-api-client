# ContactInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Person** | Pointer to **NullableString** |  | [optional] 
**Company** | Pointer to **NullableString** |  | [optional] 
**City** | Pointer to **NullableString** |  | [optional] 
**Telephone** | Pointer to **NullableString** |  | [optional] 
**Mobile** | Pointer to **NullableString** |  | [optional] 
**Address** | Pointer to **NullableString** |  | [optional] 
**PostCode** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewContactInfo

`func NewContactInfo() *ContactInfo`

NewContactInfo instantiates a new ContactInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactInfoWithDefaults

`func NewContactInfoWithDefaults() *ContactInfo`

NewContactInfoWithDefaults instantiates a new ContactInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPerson

`func (o *ContactInfo) GetPerson() string`

GetPerson returns the Person field if non-nil, zero value otherwise.

### GetPersonOk

`func (o *ContactInfo) GetPersonOk() (*string, bool)`

GetPersonOk returns a tuple with the Person field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerson

`func (o *ContactInfo) SetPerson(v string)`

SetPerson sets Person field to given value.

### HasPerson

`func (o *ContactInfo) HasPerson() bool`

HasPerson returns a boolean if a field has been set.

### SetPersonNil

`func (o *ContactInfo) SetPersonNil(b bool)`

 SetPersonNil sets the value for Person to be an explicit nil

### UnsetPerson
`func (o *ContactInfo) UnsetPerson()`

UnsetPerson ensures that no value is present for Person, not even an explicit nil
### GetCompany

`func (o *ContactInfo) GetCompany() string`

GetCompany returns the Company field if non-nil, zero value otherwise.

### GetCompanyOk

`func (o *ContactInfo) GetCompanyOk() (*string, bool)`

GetCompanyOk returns a tuple with the Company field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompany

`func (o *ContactInfo) SetCompany(v string)`

SetCompany sets Company field to given value.

### HasCompany

`func (o *ContactInfo) HasCompany() bool`

HasCompany returns a boolean if a field has been set.

### SetCompanyNil

`func (o *ContactInfo) SetCompanyNil(b bool)`

 SetCompanyNil sets the value for Company to be an explicit nil

### UnsetCompany
`func (o *ContactInfo) UnsetCompany()`

UnsetCompany ensures that no value is present for Company, not even an explicit nil
### GetCity

`func (o *ContactInfo) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *ContactInfo) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *ContactInfo) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *ContactInfo) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *ContactInfo) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *ContactInfo) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetTelephone

`func (o *ContactInfo) GetTelephone() string`

GetTelephone returns the Telephone field if non-nil, zero value otherwise.

### GetTelephoneOk

`func (o *ContactInfo) GetTelephoneOk() (*string, bool)`

GetTelephoneOk returns a tuple with the Telephone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelephone

`func (o *ContactInfo) SetTelephone(v string)`

SetTelephone sets Telephone field to given value.

### HasTelephone

`func (o *ContactInfo) HasTelephone() bool`

HasTelephone returns a boolean if a field has been set.

### SetTelephoneNil

`func (o *ContactInfo) SetTelephoneNil(b bool)`

 SetTelephoneNil sets the value for Telephone to be an explicit nil

### UnsetTelephone
`func (o *ContactInfo) UnsetTelephone()`

UnsetTelephone ensures that no value is present for Telephone, not even an explicit nil
### GetMobile

`func (o *ContactInfo) GetMobile() string`

GetMobile returns the Mobile field if non-nil, zero value otherwise.

### GetMobileOk

`func (o *ContactInfo) GetMobileOk() (*string, bool)`

GetMobileOk returns a tuple with the Mobile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobile

`func (o *ContactInfo) SetMobile(v string)`

SetMobile sets Mobile field to given value.

### HasMobile

`func (o *ContactInfo) HasMobile() bool`

HasMobile returns a boolean if a field has been set.

### SetMobileNil

`func (o *ContactInfo) SetMobileNil(b bool)`

 SetMobileNil sets the value for Mobile to be an explicit nil

### UnsetMobile
`func (o *ContactInfo) UnsetMobile()`

UnsetMobile ensures that no value is present for Mobile, not even an explicit nil
### GetAddress

`func (o *ContactInfo) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ContactInfo) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ContactInfo) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ContactInfo) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *ContactInfo) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *ContactInfo) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetPostCode

`func (o *ContactInfo) GetPostCode() string`

GetPostCode returns the PostCode field if non-nil, zero value otherwise.

### GetPostCodeOk

`func (o *ContactInfo) GetPostCodeOk() (*string, bool)`

GetPostCodeOk returns a tuple with the PostCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostCode

`func (o *ContactInfo) SetPostCode(v string)`

SetPostCode sets PostCode field to given value.

### HasPostCode

`func (o *ContactInfo) HasPostCode() bool`

HasPostCode returns a boolean if a field has been set.

### SetPostCodeNil

`func (o *ContactInfo) SetPostCodeNil(b bool)`

 SetPostCodeNil sets the value for PostCode to be an explicit nil

### UnsetPostCode
`func (o *ContactInfo) UnsetPostCode()`

UnsetPostCode ensures that no value is present for PostCode, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



# GetQuotePost200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**Data** | Pointer to [**QuoteData**](QuoteData.md) |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewGetQuotePost200Response

`func NewGetQuotePost200Response() *GetQuotePost200Response`

NewGetQuotePost200Response instantiates a new GetQuotePost200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetQuotePost200ResponseWithDefaults

`func NewGetQuotePost200ResponseWithDefaults() *GetQuotePost200Response`

NewGetQuotePost200ResponseWithDefaults instantiates a new GetQuotePost200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetQuotePost200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetQuotePost200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetQuotePost200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *GetQuotePost200Response) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetData

`func (o *GetQuotePost200Response) GetData() QuoteData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetQuotePost200Response) GetDataOk() (*QuoteData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetQuotePost200Response) SetData(v QuoteData)`

SetData sets Data field to given value.

### HasData

`func (o *GetQuotePost200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMessage

`func (o *GetQuotePost200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *GetQuotePost200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *GetQuotePost200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *GetQuotePost200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *GetQuotePost200Response) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *GetQuotePost200Response) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)



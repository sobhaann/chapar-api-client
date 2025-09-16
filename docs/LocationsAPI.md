# \LocationsAPI

All URIs are relative to *https://app.krch.ir/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCityPost**](LocationsAPI.md#GetCityPost) | **Post** /get_city | Get list of cities for a state
[**GetStateGet**](LocationsAPI.md#GetStateGet) | **Get** /get_state | Get list of states



## GetCityPost

> GetCityResponse GetCityPost(ctx).Input(input).Execute()

Get list of cities for a state



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sobhaann/chapar-api-client"
)

func main() {
	input := "input_example" // string | A stringified JSON object of type GetCityRequest.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LocationsAPI.GetCityPost(context.Background()).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LocationsAPI.GetCityPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCityPost`: GetCityResponse
	fmt.Fprintf(os.Stdout, "Response from `LocationsAPI.GetCityPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCityPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | **string** | A stringified JSON object of type GetCityRequest. | 

### Return type

[**GetCityResponse**](GetCityResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStateGet

> GetStateResponse GetStateGet(ctx).Execute()

Get list of states



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/sobhaann/chapar-api-client"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LocationsAPI.GetStateGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LocationsAPI.GetStateGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStateGet`: GetStateResponse
	fmt.Fprintf(os.Stdout, "Response from `LocationsAPI.GetStateGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetStateGetRequest struct via the builder pattern


### Return type

[**GetStateResponse**](GetStateResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


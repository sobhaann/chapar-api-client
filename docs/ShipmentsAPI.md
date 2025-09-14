# \ShipmentsAPI

All URIs are relative to *https://app.krch.ir/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkImportPost**](ShipmentsAPI.md#BulkImportPost) | **Post** /bulk_import | Import multiple shipments at once
[**CancelPickupPost**](ShipmentsAPI.md#CancelPickupPost) | **Post** /cancel_pickup | Cancel a scheduled pickup



## BulkImportPost

> BulkImportPost200Response BulkImportPost(ctx).Input(input).Signature(signature).Execute()

Import multiple shipments at once



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
	input := "input_example" // string | A stringified JSON object containing the bulk shipment data.
	signature := os.NewFile(1234, "some_file") // *os.File | An optional signature file for the shipment. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.BulkImportPost(context.Background()).Input(input).Signature(signature).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.BulkImportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkImportPost`: BulkImportPost200Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.BulkImportPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkImportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | **string** | A stringified JSON object containing the bulk shipment data. | 
 **signature** | ***os.File** | An optional signature file for the shipment. | 

### Return type

[**BulkImportPost200Response**](BulkImportPost200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelPickupPost

> BulkImportPost200Response CancelPickupPost(ctx).Input(input).Execute()

Cancel a scheduled pickup



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
	input := "input_example" // string | A stringified JSON object for the cancellation request.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.CancelPickupPost(context.Background()).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.CancelPickupPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelPickupPost`: BulkImportPost200Response
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.CancelPickupPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCancelPickupPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | **string** | A stringified JSON object for the cancellation request. | 

### Return type

[**BulkImportPost200Response**](BulkImportPost200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


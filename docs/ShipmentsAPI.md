# \ShipmentsAPI

All URIs are relative to *https://app.krch.ir/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkImportPost**](ShipmentsAPI.md#BulkImportPost) | **Post** /bulk_import | Import multiple shipments at once
[**CancelPickupPost**](ShipmentsAPI.md#CancelPickupPost) | **Post** /cancel_pickup | Cancel a scheduled pickup



## BulkImportPost

> SuccessResponse BulkImportPost(ctx).Input(input).Signature(signature).Execute()

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
	input := *openapiclient.NewBulkImportRequestInput(*openapiclient.NewUser("test", "1234"), []map[string]interface{}{map[string]interface{}(123)}) // BulkImportRequestInput | 
	signature := os.NewFile(1234, "some_file") // *os.File |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.BulkImportPost(context.Background()).Input(input).Signature(signature).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.BulkImportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkImportPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.BulkImportPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkImportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | [**BulkImportRequestInput**](BulkImportRequestInput.md) |  | 
 **signature** | ***os.File** |  | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelPickupPost

> SuccessResponse CancelPickupPost(ctx).Input(input).Execute()

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
	input := *openapiclient.NewCancelPickupRequestInput(*openapiclient.NewUser("test", "1234"), "54100004430041101") // CancelPickupRequestInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.CancelPickupPost(context.Background()).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.CancelPickupPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelPickupPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.CancelPickupPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCancelPickupPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | [**CancelPickupRequestInput**](CancelPickupRequestInput.md) |  | 

### Return type

[**SuccessResponse**](SuccessResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


# \ShipmentsAPI

All URIs are relative to *https://app.krch.ir/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkImportPost**](ShipmentsAPI.md#BulkImportPost) | **Post** /bulk_import | Import shipments in bulk
[**CancelPickupPost**](ShipmentsAPI.md#CancelPickupPost) | **Post** /cancel_pickup | Cancel a scheduled pickup



## BulkImportPost

> BulkImportResponse BulkImportPost(ctx).BulkImportRequest(bulkImportRequest).Execute()

Import shipments in bulk

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
	bulkImportRequest := *openapiclient.NewBulkImportRequest() // BulkImportRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.BulkImportPost(context.Background()).BulkImportRequest(bulkImportRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.BulkImportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkImportPost`: BulkImportResponse
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.BulkImportPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkImportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkImportRequest** | [**BulkImportRequest**](BulkImportRequest.md) |  | 

### Return type

[**BulkImportResponse**](BulkImportResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelPickupPost

> GetStateResponse CancelPickupPost(ctx).Input(input).Execute()

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
	input := "{"user":{"username":"test","password":"1234"},"consignment_no":"54100004430041101","reason":"آزمایشی"}" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ShipmentsAPI.CancelPickupPost(context.Background()).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ShipmentsAPI.CancelPickupPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelPickupPost`: GetStateResponse
	fmt.Fprintf(os.Stdout, "Response from `ShipmentsAPI.CancelPickupPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCancelPickupPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | **string** |  | 

### Return type

[**GetStateResponse**](GetStateResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


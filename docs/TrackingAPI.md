# \TrackingAPI

All URIs are relative to *https://app.krch.ir/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkHistoryReportPost**](TrackingAPI.md#BulkHistoryReportPost) | **Post** /bulk_history_report | Get a bulk history report
[**HistoryReportPost**](TrackingAPI.md#HistoryReportPost) | **Post** /history_report | Get a history report for shipments
[**TrackingPost**](TrackingAPI.md#TrackingPost) | **Post** /tracking | Track shipments by reference



## BulkHistoryReportPost

> BulkHistoryReportResponse BulkHistoryReportPost(ctx).Input(input).Execute()

Get a bulk history report



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
	input := *openapiclient.NewBulkHistoryReportRequestInput(*openapiclient.NewUser("test", "1234"), []string{"54100003992527101"}) // BulkHistoryReportRequestInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrackingAPI.BulkHistoryReportPost(context.Background()).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrackingAPI.BulkHistoryReportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkHistoryReportPost`: BulkHistoryReportResponse
	fmt.Fprintf(os.Stdout, "Response from `TrackingAPI.BulkHistoryReportPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkHistoryReportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | [**BulkHistoryReportRequestInput**](BulkHistoryReportRequestInput.md) |  | 

### Return type

[**BulkHistoryReportResponse**](BulkHistoryReportResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HistoryReportPost

> HistoryReportResponse HistoryReportPost(ctx).Input(input).Execute()

Get a history report for shipments



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
	input := *openapiclient.NewHistoryReportRequestInput(*openapiclient.NewUser("test", "1234"), *openapiclient.NewHistoryReportRequestInputDate()) // HistoryReportRequestInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrackingAPI.HistoryReportPost(context.Background()).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrackingAPI.HistoryReportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HistoryReportPost`: HistoryReportResponse
	fmt.Fprintf(os.Stdout, "Response from `TrackingAPI.HistoryReportPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiHistoryReportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | [**HistoryReportRequestInput**](HistoryReportRequestInput.md) |  | 

### Return type

[**HistoryReportResponse**](HistoryReportResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrackingPost

> SuccessResponse TrackingPost(ctx).Input(input).Execute()

Track shipments by reference



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
	input := *openapiclient.NewTrackingRequestInput(*openapiclient.NewTrackingRequestInputOrder()) // TrackingRequestInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrackingAPI.TrackingPost(context.Background()).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrackingAPI.TrackingPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrackingPost`: SuccessResponse
	fmt.Fprintf(os.Stdout, "Response from `TrackingAPI.TrackingPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTrackingPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | [**TrackingRequestInput**](TrackingRequestInput.md) |  | 

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


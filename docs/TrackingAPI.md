# \TrackingAPI

All URIs are relative to *https://app.krch.ir/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkHistoryReportPost**](TrackingAPI.md#BulkHistoryReportPost) | **Post** /bulk_history_report | Get a bulk history report
[**HistoryReportPost**](TrackingAPI.md#HistoryReportPost) | **Post** /history_report | Get a history report
[**TrackingPost**](TrackingAPI.md#TrackingPost) | **Post** /tracking | Track a shipment



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
	input := "{"user":{"username":"test","password":"1234"},"bulk":["54100003992527101","54100003942527101"]}" // string | 

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
 **input** | **string** |  | 

### Return type

[**BulkHistoryReportResponse**](BulkHistoryReportResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HistoryReportPost

> HistoryReportResponse HistoryReportPost(ctx).Input(input).Execute()

Get a history report

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
	input := "{"user":{"username":"test","password":"1234"},"date":{"from":"25-09-2017","to":"10-10-2017"},"maximum_records":10}" // string | 

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
 **input** | **string** |  | 

### Return type

[**HistoryReportResponse**](HistoryReportResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TrackingPost

> TrackingResponse TrackingPost(ctx).Input(input).Execute()

Track a shipment

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
	input := "{"order":{"reference":"54100003225544101","lang":"fa"}}" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TrackingAPI.TrackingPost(context.Background()).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TrackingAPI.TrackingPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TrackingPost`: TrackingResponse
	fmt.Fprintf(os.Stdout, "Response from `TrackingAPI.TrackingPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTrackingPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | **string** |  | 

### Return type

[**TrackingResponse**](TrackingResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


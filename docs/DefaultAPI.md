# \DefaultAPI

All URIs are relative to *https://app.krch.ir/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BulkHistoryReport**](DefaultAPI.md#BulkHistoryReport) | **Post** /bulk_history_report | Receive tracking information for N consignments in a single report. With this method, you can retrieve the tracking information for one or several bills of lading.
[**BulkImport**](DefaultAPI.md#BulkImport) | **Post** /bulk_import | Import multiple shipments at once.
[**CancelPickup**](DefaultAPI.md#CancelPickup) | **Post** /cancel_pickup | This method is used to cancel an order.
[**GetCity**](DefaultAPI.md#GetCity) | **Post** /get_city | Use this method to receive the list of cities covered by the Chapar company.
[**GetQuote**](DefaultAPI.md#GetQuote) | **Post** /get_quote | Get a shipping quote.
[**GetState**](DefaultAPI.md#GetState) | **Get** /get_state | This method is used to receive the list of provinces covered by the Chapar company.
[**HistoryReport**](DefaultAPI.md#HistoryReport) | **Post** /history_report | This method is used to receive information for each of the registered products.
[**Tracking**](DefaultAPI.md#Tracking) | **Post** /tracking | Track shipments.



## BulkHistoryReport

> BulkHistoryReportResponse BulkHistoryReport(ctx).BulkHistoryReportRequest(bulkHistoryReportRequest).Execute()

Receive tracking information for N consignments in a single report. With this method, you can retrieve the tracking information for one or several bills of lading.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/user/chapar"
)

func main() {
	bulkHistoryReportRequest := *openapiclient.NewBulkHistoryReportRequest() // BulkHistoryReportRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.BulkHistoryReport(context.Background()).BulkHistoryReportRequest(bulkHistoryReportRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.BulkHistoryReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BulkHistoryReport`: BulkHistoryReportResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.BulkHistoryReport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkHistoryReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkHistoryReportRequest** | [**BulkHistoryReportRequest**](BulkHistoryReportRequest.md) |  | 

### Return type

[**BulkHistoryReportResponse**](BulkHistoryReportResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## BulkImport

> BulkImport(ctx).APPAUTH(aPPAUTH).Input(input).Signature(signature).Execute()

Import multiple shipments at once.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/user/chapar"
)

func main() {
	aPPAUTH := "aW9zX2N1c3RvbWVyX2FwcDpUUFhAMjAxNg==" // string | 
	input := "input_example" // string |  (optional)
	signature := os.NewFile(1234, "some_file") // *os.File |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.BulkImport(context.Background()).APPAUTH(aPPAUTH).Input(input).Signature(signature).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.BulkImport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkImportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **aPPAUTH** | **string** |  | 
 **input** | **string** |  | 
 **signature** | ***os.File** |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelPickup

> CancelPickup(ctx).CancelPickupRequest(cancelPickupRequest).Execute()

This method is used to cancel an order.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/user/chapar"
)

func main() {
	cancelPickupRequest := *openapiclient.NewCancelPickupRequest() // CancelPickupRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.CancelPickup(context.Background()).CancelPickupRequest(cancelPickupRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.CancelPickup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCancelPickupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cancelPickupRequest** | [**CancelPickupRequest**](CancelPickupRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCity

> GetCityResponse GetCity(ctx).GetCityRequest(getCityRequest).Execute()

Use this method to receive the list of cities covered by the Chapar company.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/user/chapar"
)

func main() {
	getCityRequest := *openapiclient.NewGetCityRequest() // GetCityRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetCity(context.Background()).GetCityRequest(getCityRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetCity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCity`: GetCityResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetCity`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getCityRequest** | [**GetCityRequest**](GetCityRequest.md) |  | 

### Return type

[**GetCityResponse**](GetCityResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetQuote

> GetQuote(ctx).APPAUTH(aPPAUTH).Input(input).Execute()

Get a shipping quote.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/user/chapar"
)

func main() {
	aPPAUTH := "aW9zX2N1c3RvbWVyX2FwcDpUUFhAMjAxNg==" // string | 
	input := "input_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.GetQuote(context.Background()).APPAUTH(aPPAUTH).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetQuote``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetQuoteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **aPPAUTH** | **string** |  | 
 **input** | **string** |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetState

> GetStateResponse GetState(ctx).Execute()

This method is used to receive the list of provinces covered by the Chapar company.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/user/chapar"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.GetState(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.GetState``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetState`: GetStateResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.GetState`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetStateRequest struct via the builder pattern


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


## HistoryReport

> HistoryReportResponse HistoryReport(ctx).HistoryReportRequest(historyReportRequest).Execute()

This method is used to receive information for each of the registered products.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/user/chapar"
)

func main() {
	historyReportRequest := *openapiclient.NewHistoryReportRequest() // HistoryReportRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.HistoryReport(context.Background()).HistoryReportRequest(historyReportRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.HistoryReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HistoryReport`: HistoryReportResponse
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.HistoryReport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiHistoryReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **historyReportRequest** | [**HistoryReportRequest**](HistoryReportRequest.md) |  | 

### Return type

[**HistoryReportResponse**](HistoryReportResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Tracking

> Tracking(ctx).APPAUTH(aPPAUTH).Input(input).Execute()

Track shipments.

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/user/chapar"
)

func main() {
	aPPAUTH := "aW9zX2N1c3RvbWVyX2FwcDpUUFhAMjAxNg==" // string | 
	input := "input_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.Tracking(context.Background()).APPAUTH(aPPAUTH).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.Tracking``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTrackingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **aPPAUTH** | **string** |  | 
 **input** | **string** |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


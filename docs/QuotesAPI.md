# \QuotesAPI

All URIs are relative to *https://app.krch.ir/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetQuotePost**](QuotesAPI.md#GetQuotePost) | **Post** /get_quote | Get a shipping cost quote



## GetQuotePost

> QuoteResponse GetQuotePost(ctx).Input(input).Execute()

Get a shipping cost quote

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
	input := "input_example" // string | A stringified JSON object for the quote request.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QuotesAPI.GetQuotePost(context.Background()).Input(input).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QuotesAPI.GetQuotePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetQuotePost`: QuoteResponse
	fmt.Fprintf(os.Stdout, "Response from `QuotesAPI.GetQuotePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetQuotePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **input** | **string** | A stringified JSON object for the quote request. | 

### Return type

[**QuoteResponse**](QuoteResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


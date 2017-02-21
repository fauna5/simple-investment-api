# simpleInvestment.DefaultApi

All URIs are relative to *https://virtserver.swaggerhub.com/fauna5/investment/1.0.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**accountOverview**](DefaultApi.md#accountOverview) | **GET** /account | overview of account information
[**userDetails**](DefaultApi.md#userDetails) | **GET** /user | user details


<a name="accountOverview"></a>
# **accountOverview**
> [Account] accountOverview()

overview of account information

Get an overview of current account balance and portfolio

### Example
```javascript
var simpleInvestment = require('simple-investment-app-api');

var apiInstance = new simpleInvestment.DefaultApi();

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
apiInstance.accountOverview(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[Account]**](Account.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a name="userDetails"></a>
# **userDetails**
> [User] userDetails()

user details

Get basic information about the user 

### Example
```javascript
var simpleInvestment = require('simple-investment-app-api');

var apiInstance = new simpleInvestment.DefaultApi();

var callback = function(error, data, response) {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
};
apiInstance.userDetails(callback);
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**[User]**](User.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


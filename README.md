
# Getting Started with APIMATIC Calculator

## Introduction

Simple calculator API hosted on APIMATIC

## Install the Package

Install the SDK by adding the following dependency in your project's pom.xml file:

```xml
<dependency>
  <groupId>io.github.apimatic</groupId>
  <artifactId>sample-calculator-sdk-new</artifactId>
  <version>4.0.0</version>
</dependency>
```

You can also view the package at:
https://central.sonatype.com/artifact/io.github.apimatic/sample-calculator-sdk-new/4.0.0

## Initialize the API Client

**_Note:_** Documentation for the client can be found [here.](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/client.md)

The following parameters are configurable for the API Client:

| Parameter | Type | Description |
|  --- | --- | --- |
| httpClientConfig | [`Consumer<HttpClientConfiguration.Builder>`](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/http-client-configuration-builder.md) | Set up Http Client Configuration instance. |

The API client can be initialized as follows:

```java
APIMATICCalculatorClient client = new APIMATICCalculatorClient.Builder()
    .httpClientConfig(configBuilder -> configBuilder
            .timeout(0))
    .build();
```

## List of APIs

* [Simple Calculator](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/controllers/simple-calculator.md)

## SDK Infrastructure

### Configuration

* [Configuration Interface](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/configuration-interface.md)
* [HttpClientConfiguration](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/http-client-configuration.md)
* [HttpClientConfiguration.Builder](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/http-client-configuration-builder.md)

### HTTP

* [Headers](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/headers.md)
* [HttpCallback Interface](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/http-callback-interface.md)
* [HttpContext](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/http-context.md)
* [HttpBodyRequest](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/http-body-request.md)
* [HttpRequest](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/http-request.md)
* [HttpResponse](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/http-response.md)
* [HttpStringResponse](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/http-string-response.md)

### Utilities

* [ApiException](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/api-exception.md)
* [ApiHelper](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/api-helper.md)
* [FileWrapper](https://www.github.com/sufyankhanrao/calculator-sdk-java-sdk/tree/4.0.0/doc/file-wrapper.md)


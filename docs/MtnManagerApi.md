# MtnManagerApi

All URIs are relative to *https://your-resort.mtnmanager.com*

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**getAmenities**](MtnManagerApi.md#getAmenities) | **GET** /api/v1/report/amenities | Get amenities |
| [**getAppReport**](MtnManagerApi.md#getAppReport) | **GET** /api/v1/report/app | Get app report |
| [**getFullReport**](MtnManagerApi.md#getFullReport) | **GET** /api/v1/report | Get full report |
| [**getHours**](MtnManagerApi.md#getHours) | **GET** /api/v1/report/hours | Get operating hours |
| [**getLifts**](MtnManagerApi.md#getLifts) | **GET** /api/v1/report/lifts | Get lifts |
| [**getOverview**](MtnManagerApi.md#getOverview) | **GET** /api/v1/report/overview | Get overview |
| [**getParkingLots**](MtnManagerApi.md#getParkingLots) | **GET** /api/v1/report/parking-lots | Get parking lots |
| [**getRuns**](MtnManagerApi.md#getRuns) | **GET** /api/v1/report/runs | Get runs |
| [**getSnow**](MtnManagerApi.md#getSnow) | **GET** /api/v1/report/snow | Get snow conditions |
| [**getSummerTrails**](MtnManagerApi.md#getSummerTrails) | **GET** /api/v1/report/summer-trails | Get summer trails |
| [**getTerrainParks**](MtnManagerApi.md#getTerrainParks) | **GET** /api/v1/report/terrain-parks | Get terrain parks |
| [**getTrailMap**](MtnManagerApi.md#getTrailMap) | **GET** /api/v1/report/trail-map/{uuid} | Get trail map |
| [**getTrailMapStatic**](MtnManagerApi.md#getTrailMapStatic) | **GET** /api/v1/report/trail-map/{uuid}/static/{version} | Get static trail map |
| [**getTrailMaps**](MtnManagerApi.md#getTrailMaps) | **GET** /api/v1/report/trail-maps | Get trail maps |
| [**getWeather**](MtnManagerApi.md#getWeather) | **GET** /api/v1/report/weather | Get weather |
| [**getWebcamHistory**](MtnManagerApi.md#getWebcamHistory) | **GET** /api/v1/report/webcam/{uuid}/history | Get webcam history |
| [**getWebcams**](MtnManagerApi.md#getWebcams) | **GET** /api/v1/report/webcams | Get webcams |


<a id="getAmenities"></a>
# **getAmenities**
> kotlin.collections.List&lt;Amenity&gt; getAmenities(acceptLanguage)

Get amenities

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<Amenity> = apiInstance.getAmenities(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getAmenities")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getAmenities")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;Amenity&gt;**](Amenity.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getAppReport"></a>
# **getAppReport**
> AppReport getAppReport(acceptLanguage)

Get app report

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : AppReport = apiInstance.getAppReport(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getAppReport")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getAppReport")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**AppReport**](AppReport.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getFullReport"></a>
# **getFullReport**
> FullReport getFullReport(acceptLanguage)

Get full report

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : FullReport = apiInstance.getFullReport(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getFullReport")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getFullReport")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**FullReport**](FullReport.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getHours"></a>
# **getHours**
> OperatingHours getHours(acceptLanguage)

Get operating hours

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : OperatingHours = apiInstance.getHours(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getHours")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getHours")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**OperatingHours**](OperatingHours.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getLifts"></a>
# **getLifts**
> kotlin.collections.List&lt;Lift&gt; getLifts(acceptLanguage)

Get lifts

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<Lift> = apiInstance.getLifts(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getLifts")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getLifts")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;Lift&gt;**](Lift.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getOverview"></a>
# **getOverview**
> Overview getOverview(acceptLanguage)

Get overview

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : Overview = apiInstance.getOverview(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getOverview")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getOverview")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**Overview**](Overview.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getParkingLots"></a>
# **getParkingLots**
> kotlin.collections.List&lt;ParkingLot&gt; getParkingLots(acceptLanguage)

Get parking lots

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<ParkingLot> = apiInstance.getParkingLots(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getParkingLots")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getParkingLots")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;ParkingLot&gt;**](ParkingLot.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getRuns"></a>
# **getRuns**
> kotlin.collections.List&lt;Run&gt; getRuns(acceptLanguage)

Get runs

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<Run> = apiInstance.getRuns(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getRuns")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getRuns")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;Run&gt;**](Run.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getSnow"></a>
# **getSnow**
> kotlin.collections.List&lt;SnowReport&gt; getSnow(acceptLanguage)

Get snow conditions

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<SnowReport> = apiInstance.getSnow(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getSnow")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getSnow")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;SnowReport&gt;**](SnowReport.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getSummerTrails"></a>
# **getSummerTrails**
> kotlin.collections.List&lt;SummerTrail&gt; getSummerTrails(acceptLanguage)

Get summer trails

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<SummerTrail> = apiInstance.getSummerTrails(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getSummerTrails")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getSummerTrails")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;SummerTrail&gt;**](SummerTrail.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getTerrainParks"></a>
# **getTerrainParks**
> kotlin.collections.List&lt;TerrainPark&gt; getTerrainParks(acceptLanguage)

Get terrain parks

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<TerrainPark> = apiInstance.getTerrainParks(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getTerrainParks")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getTerrainParks")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;TerrainPark&gt;**](TerrainPark.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getTrailMap"></a>
# **getTrailMap**
> TrailMap getTrailMap(uuid, acceptLanguage)

Get trail map

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val uuid : kotlin.String = uuid_example // kotlin.String | Resource UUID
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : TrailMap = apiInstance.getTrailMap(uuid, acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getTrailMap")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getTrailMap")
    e.printStackTrace()
}
```

### Parameters
| **uuid** | **kotlin.String**| Resource UUID | |
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**TrailMap**](TrailMap.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getTrailMapStatic"></a>
# **getTrailMapStatic**
> TrailMapStatic getTrailMapStatic(uuid, version, acceptLanguage)

Get static trail map

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val uuid : kotlin.String = uuid_example // kotlin.String | Trail map UUID
val version : kotlin.Long = 789 // kotlin.Long | The map version being requested (from `TrailMapSummary.version`)
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : TrailMapStatic = apiInstance.getTrailMapStatic(uuid, version, acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getTrailMapStatic")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getTrailMapStatic")
    e.printStackTrace()
}
```

### Parameters
| **uuid** | **kotlin.String**| Trail map UUID | |
| **version** | **kotlin.Long**| The map version being requested (from &#x60;TrailMapSummary.version&#x60;) | |
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**TrailMapStatic**](TrailMapStatic.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getTrailMaps"></a>
# **getTrailMaps**
> kotlin.collections.List&lt;TrailMapSummary&gt; getTrailMaps(acceptLanguage)

Get trail maps

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<TrailMapSummary> = apiInstance.getTrailMaps(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getTrailMaps")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getTrailMaps")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;TrailMapSummary&gt;**](TrailMapSummary.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getWeather"></a>
# **getWeather**
> kotlin.collections.List&lt;Weather&gt; getWeather(acceptLanguage)

Get weather

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<Weather> = apiInstance.getWeather(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getWeather")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getWeather")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;Weather&gt;**](Weather.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getWebcamHistory"></a>
# **getWebcamHistory**
> WebcamHistoryResponse getWebcamHistory(uuid, from, to, acceptLanguage)

Get webcam history

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val uuid : kotlin.String = uuid_example // kotlin.String | Resource UUID
val from : kotlin.String = from_example // kotlin.String | Inclusive lower bound on `captured_at` (RFC 3339).
val to : kotlin.String = to_example // kotlin.String | Inclusive upper bound on `captured_at` (RFC 3339).
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : WebcamHistoryResponse = apiInstance.getWebcamHistory(uuid, from, to, acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getWebcamHistory")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getWebcamHistory")
    e.printStackTrace()
}
```

### Parameters
| **uuid** | **kotlin.String**| Resource UUID | |
| **from** | **kotlin.String**| Inclusive lower bound on &#x60;captured_at&#x60; (RFC 3339). | [optional] [default to &quot;null&quot;] |
| **to** | **kotlin.String**| Inclusive upper bound on &#x60;captured_at&#x60; (RFC 3339). | [optional] [default to &quot;null&quot;] |
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**WebcamHistoryResponse**](WebcamHistoryResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

<a id="getWebcams"></a>
# **getWebcams**
> kotlin.collections.List&lt;Webcam&gt; getWebcams(acceptLanguage)

Get webcams

### Example
```kotlin
// Import classes:
//import com.mtnmanager.sdk.infrastructure.*
//import com.mtnmanager.sdk.models.*

val apiInstance = MtnManagerApi()
val acceptLanguage : kotlin.String = fr-CA // kotlin.String | Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports `en`, `fr`, `de`, `it`, and `es`, with optional region tags such as `fr-CA` or `de-CH`. Defaults to English when omitted or unsupported.
try {
    val result : kotlin.collections.List<Webcam> = apiInstance.getWebcams(acceptLanguage)
    println(result)
} catch (e: ClientException) {
    println("4xx response calling MtnManagerApi#getWebcams")
    e.printStackTrace()
} catch (e: ServerException) {
    println("5xx response calling MtnManagerApi#getWebcams")
    e.printStackTrace()
}
```

### Parameters
| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **acceptLanguage** | **kotlin.String**| Preferred language and optional region for human-readable strings in the response (e.g. operating hours summaries). Supports &#x60;en&#x60;, &#x60;fr&#x60;, &#x60;de&#x60;, &#x60;it&#x60;, and &#x60;es&#x60;, with optional region tags such as &#x60;fr-CA&#x60; or &#x60;de-CH&#x60;. Defaults to English when omitted or unsupported. | [optional] |

### Return type

[**kotlin.collections.List&lt;Webcam&gt;**](Webcam.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


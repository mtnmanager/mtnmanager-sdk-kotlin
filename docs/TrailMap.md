
# TrailMap

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** |  |  |
| **name** | **kotlin.String** |  |  |
| **slug** | **kotlin.String** |  |  |
| **season** | [**SeasonType**](SeasonType.md) |  |  |
| **displayOrder** | **kotlin.Long** |  |  |
| **version** | **kotlin.Long** | Monotonically incremented on every update. Clients can compare this  against a cached value to decide whether to reload the trail map. |  |
| **backgroundImageUrl** | **kotlin.String** |  |  |
| **resort** | [**ResortInfo**](ResortInfo.md) |  |  |
| **elements** | [**kotlin.collections.List&lt;TrailMapElement&gt;**](TrailMapElement.md) |  |  |
| **geoControlPoints** | [**kotlin.collections.List&lt;GeoControlPoint&gt;**](GeoControlPoint.md) |  |  [optional] |




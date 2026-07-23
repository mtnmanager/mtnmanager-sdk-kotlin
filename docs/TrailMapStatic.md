
# TrailMapStatic

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** |  |  |
| **name** | **kotlin.String** |  |  |
| **slug** | **kotlin.String** |  |  |
| **season** | [**SeasonType**](SeasonType.md) |  |  |
| **displayOrder** | **kotlin.Long** |  |  |
| **version** | **kotlin.Long** | Monotonically incremented whenever the map&#39;s static content (geometry,  artwork, element membership, or the metadata carried here) changes. This  body is byte-stable for a fixed &#x60;version&#x60;, and the &#x60;version&#x60; is part of  the request URL — so the resource is immutable per version. |  |
| **backgroundImageUrl** | **kotlin.String** |  |  |
| **elements** | [**kotlin.collections.List&lt;TrailMapStaticElement&gt;**](TrailMapStaticElement.md) |  |  |
| **geoControlPoints** | [**kotlin.collections.List&lt;GeoControlPoint&gt;**](GeoControlPoint.md) |  |  [optional] |




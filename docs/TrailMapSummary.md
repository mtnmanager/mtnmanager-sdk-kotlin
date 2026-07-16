
# TrailMapSummary

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** |  |  |
| **name** | **kotlin.String** |  |  |
| **season** | [**SeasonType**](SeasonType.md) |  |  |
| **displayOrder** | **kotlin.Long** |  |  |
| **version** | **kotlin.Long** | Monotonically incremented on every update. Clients can compare this  against a cached value to decide whether to reload the trail map. |  |
| **hostedUrl** | **kotlin.String** |  |  |
| **entityUuids** | **kotlin.collections.List&lt;kotlin.String&gt;** | Deduplicated UUIDs of every entity (lift, run, terrain park,  summer trail, amenity, parking lot) referenced by this map&#39;s elements. |  |
| **geoBounds** | [**GeoBounds**](GeoBounds.md) | Lat/lng bounding box of this map&#39;s georeferenced area, plus the  centroid of its control points (used for tie-breaking when multiple  maps cover the same point). Omitted when the map has no georeferencing. |  [optional] |




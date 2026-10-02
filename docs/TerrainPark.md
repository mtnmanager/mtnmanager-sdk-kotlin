
# TerrainPark

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** | Unique identifier for the terrain park. |  |
| **name** | **kotlin.String** | Display name of the terrain park. |  |
| **slug** | **kotlin.String** | URL-friendly name of the terrain park. |  |
| **status** | [**TerrainParkStatus**](TerrainParkStatus.md) | Current operational status (open, closed, or unknown). |  |
| **groomedToday** | **kotlin.Boolean** | Whether the terrain park was groomed within the last 24 hours. |  |
| **conditionNotes** | **kotlin.String** | Notes about current conditions in this terrain park. |  |
| **features** | [**kotlin.collections.List&lt;TerrainParkFeature&gt;**](TerrainParkFeature.md) | Features within this terrain park (jumps, boxes, rails, etc.). |  |
| **updatedAt** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When this terrain park or any of its features was last updated. |  |
| **number** | **kotlin.Int** | Optional terrain park number. |  [optional] |
| **lastGroomed** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When the terrain park was last groomed.  &#x60;null&#x60; if never groomed, or if the terrain park grooming feature is disabled. |  [optional] |
| **areaUuid** | **kotlin.String** | UUID of the area this terrain park belongs to, if assigned. |  [optional] |
| **areaName** | **kotlin.String** | Name of the area this terrain park belongs to, if assigned. |  [optional] |
| **areaDisplayOrder** | **kotlin.Int** | Display order of the area this terrain park belongs to, if assigned, for sorting purposes. |  [optional] |
| **images** | [**kotlin.collections.List&lt;EntityImage&gt;**](EntityImage.md) | Images attached to this terrain park, ordered for display. Each includes  a ThumbHash for rendering a blurred placeholder while the image loads. |  [optional] |




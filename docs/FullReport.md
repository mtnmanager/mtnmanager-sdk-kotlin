
# FullReport

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **resort** | [**ResortInfo**](ResortInfo.md) |  |  |
| **status** | [**Overview**](Overview.md) |  |  |
| **snow** | [**kotlin.collections.List&lt;SnowReport&gt;**](SnowReport.md) | Provides current snow conditions including base depth, surface conditions,  and snowfall totals in both metric and imperial units.   May contain multiple, representing different reporting areas. |  |
| **lifts** | [**kotlin.collections.List&lt;Lift&gt;**](Lift.md) | List of all lifts at the resort with their current operational status,  type, and optional wait time information. |  |
| **runs** | [**kotlin.collections.List&lt;Run&gt;**](Run.md) | List of all runs at the resort with their current status,  grooming information, and difficulty rating. |  |
| **terrainParks** | [**kotlin.collections.List&lt;TerrainPark&gt;**](TerrainPark.md) | List of all terrain parks at the resort with their current status,  condition notes, and list of features (jumps, boxes, rails, etc.) within them. |  |
| **parkingLots** | [**kotlin.collections.List&lt;ParkingLot&gt;**](ParkingLot.md) | List of all parking lots at the resort with their current status and amenities. |  |
| **summerTrails** | [**kotlin.collections.List&lt;SummerTrail&gt;**](SummerTrail.md) | List of all summer trails at the resort with their current status,  type (e.g. hiking, mountain biking), and optional difficulty rating. |  |
| **hours** | [**OperatingHours**](OperatingHours.md) |  |  |
| **weather** | [**kotlin.collections.List&lt;Weather&gt;**](Weather.md) | Weather entries: the resort-wide entry first (current + forecast), then  any per-area current-conditions entries. Empty when weather is disabled  or unavailable. |  [optional] |
| **webcams** | [**kotlin.collections.List&lt;Webcam&gt;**](Webcam.md) | Enabled webcams with the URLs of their current and last-daylight frames  plus thumbnails. Empty when the resort does not have webcams. |  [optional] |




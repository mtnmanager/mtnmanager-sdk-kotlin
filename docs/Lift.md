
# Lift

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** | Unique identifier for the lift. |  |
| **name** | **kotlin.String** | Display name of the lift. |  |
| **slug** | **kotlin.String** | URL-friendly name of the lift. |  |
| **liftType** | [**LiftType**](LiftType.md) | Type of lift (e.g. gondola, quad). |  |
| **highSpeed** | **kotlin.Boolean** | Whether this is a high-speed/detachable lift. |  |
| **bubble** | **kotlin.Boolean** | Whether the lift has a bubble/cover for weather protection. |  |
| **heated** | **kotlin.Boolean** | Whether the lift has heated seats. |  |
| **status** | [**LiftStatus**](LiftStatus.md) | Current operational status (open, closed, on_hold, or unknown). |  |
| **updatedAt** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When this lift&#39;s information was last updated. |  |
| **number** | **kotlin.Int** | Optional lift number. |  [optional] |
| **capacity** | **kotlin.Int** | Riders per chair or cabin, if available. |  [optional] |
| **travelTime** | **kotlin.Double** | Estimated travel time in minutes. |  [optional] |
| **lengthFt** | **kotlin.Int** | Length of the lift in feet. |  [optional] |
| **lengthM** | **kotlin.Int** | Length of the lift in meters. |  [optional] |
| **verticalRiseFt** | **kotlin.Int** | Vertical rise of the lift in feet. |  [optional] |
| **verticalRiseM** | **kotlin.Int** | Vertical rise of the lift in meters. |  [optional] |
| **waitTimeMinutes** | **kotlin.Long** | Current estimated wait time in minutes, if available. |  [optional] |
| **opensAt** | **kotlin.String** | Today&#39;s scheduled opening time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if the lift has no scheduled hours for today. |  [optional] |
| **closesAt** | **kotlin.String** | Today&#39;s scheduled closing time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if the lift has no scheduled hours for today. |  [optional] |
| **areaUuid** | **kotlin.String** | UUID of the area this lift belongs to, if assigned. |  [optional] |
| **areaName** | **kotlin.String** | Name of the area this lift belongs to, if assigned. |  [optional] |
| **areaDisplayOrder** | **kotlin.Int** | Display order of the area this lift belongs to, if assigned, for sorting purposes. |  [optional] |
| **images** | [**kotlin.collections.List&lt;EntityImage&gt;**](EntityImage.md) | Images attached to this lift, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. |  [optional] |




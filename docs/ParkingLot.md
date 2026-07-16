
# ParkingLot

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** | Unique identifier for the parking lot. |  |
| **name** | **kotlin.String** | Display name of the parking lot. |  |
| **slug** | **kotlin.String** | URL-friendly name of the parking lot. |  |
| **status** | [**ParkingLotStatus**](ParkingLotStatus.md) | Current status (open, closed, or full). |  |
| **shuttle** | **kotlin.Boolean** | Whether shuttle service is available from this lot. |  |
| **paid** | **kotlin.Boolean** | Whether parking is paid/requires payment. |  |
| **reservationRequired** | **kotlin.Boolean** | Whether a reservation is required to park here. |  |
| **updatedAt** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When this parking lot&#39;s information was last updated. |  |
| **capacity** | **kotlin.Int** | Maximum vehicle capacity, if set. |  [optional] |
| **images** | [**kotlin.collections.List&lt;EntityImage&gt;**](EntityImage.md) | Images attached to this parking lot, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. |  [optional] |




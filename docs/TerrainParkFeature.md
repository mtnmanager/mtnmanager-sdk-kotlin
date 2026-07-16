
# TerrainParkFeature

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** | Unique identifier for the feature. |  |
| **name** | **kotlin.String** | Display name of the feature. |  |
| **slug** | **kotlin.String** | URL-friendly name of the run. |  |
| **featureType** | [**FeatureType**](FeatureType.md) | Type of feature (jump, box, rail, other). |  |
| **status** | [**TerrainParkFeatureStatus**](TerrainParkFeatureStatus.md) | Current operational status (open, closed, or unknown).  &#x60;unknown&#x60; unless the terrain park feature status is enabled. |  |
| **number** | **kotlin.Int** | Optional feature number. |  [optional] |
| **propertySize** | [**FeatureSize**](FeatureSize.md) | Optional size rating of the feature (S, M, L, XL). |  [optional] |
| **images** | [**kotlin.collections.List&lt;EntityImage&gt;**](EntityImage.md) | Images attached to this feature, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. |  [optional] |




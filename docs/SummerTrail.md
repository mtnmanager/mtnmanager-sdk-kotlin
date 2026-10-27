
# SummerTrail

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** | Unique identifier for the trail. |  |
| **name** | **kotlin.String** | Display name of the trail. |  |
| **slug** | **kotlin.String** | URL-friendly name of the trail. |  |
| **activities** | [**kotlin.collections.List&lt;SummerTrailActivity&gt;**](SummerTrailActivity.md) | Activities the trail is open to (e.g. hiking, mountain_biking,  on_leash_dogs). Can have multiple. |  |
| **status** | [**SummerTrailStatus**](SummerTrailStatus.md) | Current operational status (open, closed, or unknown). |  |
| **conditionNotes** | **kotlin.String** | Notes about current conditions on this trail. |  |
| **updatedAt** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When this trail&#39;s information was last updated. |  |
| **number** | **kotlin.Int** | Optional trail number. |  [optional] |
| **difficulty** | [**SummerTrailDifficulty**](SummerTrailDifficulty.md) | Difficulty rating of the trail (optional for summer trails). |  [optional] |
| **difficultyType** | [**SummerTrailDifficultyType**](SummerTrailDifficultyType.md) | The rating system the difficulty is shown in, which picks its icon:  &#x60;null&#x60; for the standard one, or a mountain-bike freeride / technical one. |  [optional] |
| **areaUuid** | **kotlin.String** | UUID of the area this trail belongs to, if assigned. |  [optional] |
| **areaName** | **kotlin.String** | Name of the area this trail belongs to, if assigned. |  [optional] |
| **areaDisplayOrder** | **kotlin.Int** | Display order of the area this trail belongs to, if assigned, for sorting purposes. |  [optional] |
| **images** | [**kotlin.collections.List&lt;EntityImage&gt;**](EntityImage.md) | Images attached to this trail, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. |  [optional] |




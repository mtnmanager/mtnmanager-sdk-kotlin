
# Run

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** | Unique identifier for the run. |  |
| **name** | **kotlin.String** | Display name of the run. |  |
| **slug** | **kotlin.String** | URL-friendly name of the run. |  |
| **difficulty** | [**RunDifficulty**](RunDifficulty.md) | Difficulty rating of the run. |  |
| **status** | [**RunStatus**](RunStatus.md) | Current operational status (open, closed, or unknown). |  |
| **groomedToday** | **kotlin.Boolean** | Whether the run has been groomed since the resort last closed (or,  for a resort with no operating hours set, within the last 24 hours). |  |
| **snowmaking** | **kotlin.Boolean** | Whether the run has snowmaking capabilities. |  |
| **nightSkiing** | **kotlin.Boolean** | Whether the run is available for night skiing. |  |
| **conditionNotes** | **kotlin.String** | Notes about current conditions on this run. |  |
| **updatedAt** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When this run&#39;s information was last updated. |  |
| **number** | **kotlin.Int** | Optional run number. |  [optional] |
| **lastGroomed** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When the run was last groomed.  &#x60;null&#x60; if not groomed this season (since the snow year began: Aug 1, or  Jan 1 in the southern hemisphere), or if the runs grooming feature is disabled. |  [optional] |
| **snowSinceGroomedCm** | **kotlin.Int** | New snow (cm) reported since &#x60;last_groomed&#x60; (\&quot;groomed with fresh\&quot;).  Absent unless the run was groomed within the last 24 hours and the  resort keeps a snow report. |  [optional] |
| **snowSinceGroomedIn** | **kotlin.Int** | New snow (inches) reported since &#x60;last_groomed&#x60;; see  &#x60;snow_since_groomed_cm&#x60;. |  [optional] |
| **areaUuid** | **kotlin.String** | UUID of the area this run belongs to, if assigned. |  [optional] |
| **areaName** | **kotlin.String** | Name of the area this run belongs to, if assigned. |  [optional] |
| **areaDisplayOrder** | **kotlin.Int** | Display order of the area this run belongs to, if assigned, for sorting purposes. |  [optional] |
| **images** | [**kotlin.collections.List&lt;EntityImage&gt;**](EntityImage.md) | Images attached to this run, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. |  [optional] |




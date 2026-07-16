
# Webcam

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** |  |  |
| **name** | **kotlin.String** |  |  |
| **latestImageUrl** | **kotlin.String** | URL of the newest frame (refreshes within ~60s via the edge cache). |  |
| **latestDaylightImageUrl** | **kotlin.String** | URL of the last daylight frame. |  |
| **latestThumbUrl** | **kotlin.String** |  |  |
| **latestDaylightThumbUrl** | **kotlin.String** |  |  |
| **latestThumbhash** | **kotlin.String** | ThumbHash of the &#x60;latest&#x60; frame (standard base64) — a compact blur  placeholder to render while the image loads. Empty string until the first  frame (or on cameras predating the feature). |  |
| **latestDaylightThumbhash** | **kotlin.String** | ThumbHash of the &#x60;latest-daylight&#x60; frame (standard base64). Empty string  until the first daylight frame. |  |
| **hasHistory** | **kotlin.Boolean** | Whether this camera archives frames — i.e. whether its history endpoint  returns anything. When &#x60;false&#x60;, don&#39;t call the history API for it. |  |
| **areaUuid** | **kotlin.String** |  |  [optional] |
| **areaName** | **kotlin.String** |  |  [optional] |
| **areaDisplayOrder** | **kotlin.Int** |  |  [optional] |
| **elevationFt** | **kotlin.Int** | Camera elevation in both units; omitted when unset. |  [optional] |
| **elevationM** | **kotlin.Int** |  |  [optional] |
| **lastFrameAt** | **kotlin.String** | Time of the most recently published frame; omitted until the first frame. |  [optional] |




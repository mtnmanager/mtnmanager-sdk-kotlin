
# Overview

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **status** | [**ResortStatus**](ResortStatus.md) | Current operational status of the resort (open or closed).  This is calculated based on the current time relative to today&#39;s scheduled hours. |  |
| **season** | [**SeasonType**](SeasonType.md) | Current operating season (winter, summer, or closed/off-season). |  |
| **news** | [**kotlin.collections.List&lt;OverviewNews&gt;**](OverviewNews.md) | Written news — daily update, announcements, etc. The resort&#39;s primary  news comes first, followed by any others it publishes, in the order they  were added. News with nothing written is still listed, with empty  &#x60;raw&#x60; and &#x60;html&#x60;. |  |
| **runs** | [**OverviewRuns**](OverviewRuns.md) | Run statistics: counts, acres, and last-updated timestamp. |  |
| **lifts** | [**OverviewLifts**](OverviewLifts.md) | Lift statistics: counts and last-updated timestamp. |  |
| **summerTrails** | [**OverviewSummerTrails**](OverviewSummerTrails.md) | Summer trail statistics: counts and last-updated timestamp. |  |
| **terrainParks** | [**OverviewTerrainParks**](OverviewTerrainParks.md) | Terrain park statistics: counts and last-updated timestamp. |  |
| **opensAt** | **kotlin.String** | Today&#39;s scheduled opening time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. |  [optional] |
| **closesAt** | **kotlin.String** | Today&#39;s scheduled closing time in 24-hour format (HH:MM).  &#x60;null&#x60; if the resort is not scheduled to open today. |  [optional] |




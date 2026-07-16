
# Weather

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **current** | [**CurrentWeather**](CurrentWeather.md) | Current weather conditions |  |
| **hourlyForecast** | [**kotlin.collections.List&lt;HourlyForecast&gt;**](HourlyForecast.md) | Hourly forecast for next 24 hours (including current hour) |  |
| **dailyForecast** | [**kotlin.collections.List&lt;DailyForecast&gt;**](DailyForecast.md) | Daily forecast for next 7 days (including today) |  |
| **attribution** | **kotlin.String** | Data source attribution |  |
| **updatedAt** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When this data was last updated |  |
| **areaUuid** | **kotlin.String** | The area this weather belongs to, or omitted for resort-wide weather. |  [optional] |
| **areaName** | **kotlin.String** | The area&#39;s name, or omitted for resort-wide weather. |  [optional] |
| **areaDisplayOrder** | **kotlin.Int** | The area&#39;s display order, or omitted for resort-wide weather. |  [optional] |





# HourlyForecast

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **timestamp** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | Forecast timestamp |  |
| **imperial** | [**HourlyForecastImperial**](HourlyForecastImperial.md) | Measurements in imperial units |  |
| **metric** | [**HourlyForecastMetric**](HourlyForecastMetric.md) | Measurements in metric units |  |
| **condition** | **kotlin.String** | Human-readable condition |  |
| **conditionCode** | [**WeatherConditionCode**](WeatherConditionCode.md) | Weather condition code |  |
| **precipitationProbability** | **kotlin.Int** | Probability of precipitation (0-100%) |  [optional] |




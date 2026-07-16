
# DailyForecast

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **date** | [**java.time.LocalDate**](java.time.LocalDate.md) | Date of forecast (YYYY-MM-DD format) |  |
| **imperial** | [**DailyForecastImperial**](DailyForecastImperial.md) | Measurements in imperial units |  |
| **metric** | [**DailyForecastMetric**](DailyForecastMetric.md) | Measurements in metric units |  |
| **condition** | **kotlin.String** | Human-readable condition |  |
| **conditionCode** | [**WeatherConditionCode**](WeatherConditionCode.md) | Condition code |  |
| **sunrise** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | Sunrise time |  |
| **sunset** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | Sunset time |  |
| **precipitationProbability** | **kotlin.Int** | Probability of precipitation (0-100%) |  [optional] |




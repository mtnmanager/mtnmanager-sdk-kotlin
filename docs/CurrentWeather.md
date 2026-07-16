
# CurrentWeather

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **imperial** | [**CurrentWeatherImperial**](CurrentWeatherImperial.md) | Measurements in imperial units |  |
| **metric** | [**CurrentWeatherMetric**](CurrentWeatherMetric.md) | Measurements in metric units |  |
| **condition** | **kotlin.String** | Human-readable weather condition |  |
| **conditionCode** | [**WeatherConditionCode**](WeatherConditionCode.md) | Weather condition code |  |
| **timestamp** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | Timestamp of observation |  |
| **windDirection** | **kotlin.Int** | Wind direction in degrees (0-360) |  [optional] |
| **windDirectionCardinal** | **kotlin.String** | Wind direction as cardinal direction (N, NE, E, SE, S, SW, W, NW) |  [optional] |




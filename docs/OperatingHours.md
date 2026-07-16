
# OperatingHours

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **schedules** | [**kotlin.collections.List&lt;Schedule&gt;**](Schedule.md) | Recurring operating schedules currently in effect or upcoming.  Excludes single-day overrides and past schedules. |  |
| **calendarDays** | [**kotlin.collections.List&lt;CalendarDay&gt;**](CalendarDay.md) | List of all days the resort is open (or a closure override).  Ordered chronologically, spanning from the earliest scheduled date  to the latest scheduled date in the currently defined operating hours. |  |
| **amenitySchedules** | [**kotlin.collections.List&lt;AmenitySchedule&gt;**](AmenitySchedule.md) | Per-amenity operating schedules. Only included when amenity hours are configured. |  [optional] |




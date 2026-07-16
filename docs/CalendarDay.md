
# CalendarDay

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **date** | [**java.time.LocalDate**](java.time.LocalDate.md) | Calendar date (YYYY-MM-DD). |  |
| **dayOfWeek** | [**DayOfWeek**](DayOfWeek.md) | Day of the week. |  |
| **isOpen** | **kotlin.Boolean** | Whether the resort is open on this day. |  |
| **opensAt** | **kotlin.String** | Opening time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if closed on this day. |  [optional] |
| **closesAt** | **kotlin.String** | Closing time in 24-hour format (HH:MM), in resort&#39;s local timezone.  &#x60;null&#x60; if closed on this day. |  [optional] |
| **closureReason** | [**ClosureReason**](ClosureReason.md) | Optional reason code for closure. |  [optional] |
| **specialEvent** | **kotlin.String** | Special event for this day. |  [optional] |
| **amenities** | [**kotlin.collections.List&lt;AmenityCalendarEntry&gt;**](AmenityCalendarEntry.md) | Per-amenity hours for this day. Only included when amenity hours are configured. |  [optional] |





# Schedule

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **daysString** | **kotlin.String** | Human-readable description of which days this schedule applies to.  Examples: \&quot;Daily\&quot;, \&quot;Saturday &amp; Sunday\&quot;, \&quot;Monday, Wednesday, and Friday\&quot; |  |
| **daysOfWeek** | [**kotlin.collections.List&lt;DayOfWeek&gt;**](DayOfWeek.md) | Array of days of the week this schedule applies to.  For programmatic use. |  |
| **timeString** | **kotlin.String** | Human-readable time range.  Example: \&quot;9:00 AM to 4:00 PM\&quot; |  |
| **opensAt** | **kotlin.String** | Opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. |  |
| **closesAt** | **kotlin.String** | Closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. |  |
| **inEffect** | **kotlin.Boolean** | Whether this schedule is currently in effect.  &#x60;false&#x60; for upcoming schedules that haven&#39;t started yet. |  |
| **effectiveString** | **kotlin.String** | Human-readable date range when this schedule is effective.  Example: \&quot;November 1, 2024 to April 15, 2025\&quot; |  |
| **effectiveFrom** | [**java.time.LocalDate**](java.time.LocalDate.md) | Start date of the effective period (YYYY-MM-DD). |  |
| **effectiveTo** | [**java.time.LocalDate**](java.time.LocalDate.md) | End date of the effective period (YYYY-MM-DD). |  |





# Amenity

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **description** | **kotlin.String** | Description of the amenity. |  |
| **uuid** | **kotlin.String** | Unique identifier for the amenity. |  |
| **name** | **kotlin.String** | Display name of the amenity. |  |
| **category** | [**AmenityCategory**](AmenityCategory.md) | Category classification (e.g. restaurant, lodge, ski_school). |  |
| **website** | **kotlin.String** | Website URL for the amenity, if available. |  |
| **hasOperatingHours** | **kotlin.Boolean** | Whether this amenity reports operating hours. When false, clients should  not expect &#x60;opens_at&#x60;, &#x60;closes_at&#x60;, or &#x60;schedules&#x60; to ever be populated. |  |
| **schedules** | [**kotlin.collections.List&lt;Schedule&gt;**](Schedule.md) | Recurring operating schedules for this amenity (e.g. \&quot;Saturday &amp; Sunday,  9:00 a.m. to 4:00 p.m.\&quot;), with both human-readable and structured fields. |  |
| **opensAt** | **kotlin.String** | Today&#39;s scheduled opening time in 24-hour format (HH:MM), in resort&#39;s local timezone. |  [optional] |
| **closesAt** | **kotlin.String** | Today&#39;s scheduled closing time in 24-hour format (HH:MM), in resort&#39;s local timezone. |  [optional] |
| **images** | [**kotlin.collections.List&lt;EntityImage&gt;**](EntityImage.md) | Images attached to this amenity, ordered for display. Each includes a  ThumbHash for rendering a blurred placeholder while the image loads. |  [optional] |




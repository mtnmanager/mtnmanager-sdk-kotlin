
# OverviewNews

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **uuid** | **kotlin.String** | Stable identifier of this news feed. |  |
| **isPrimary** | **kotlin.Boolean** | Whether this is the resort&#39;s primary news feed. Exactly one news is. |  |
| **raw** | **kotlin.String** | Markdown source. Images the resort uploaded point at their public URLs,  so any Markdown renderer can display them. |  |
| **html** | **kotlin.String** | Rendered HTML (from Markdown) |  |
| **updatedAt** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When the news was last updated. |  |
| **name** | **kotlin.String** | The name the resort gave this news feed, for telling several apart.  May be &#x60;null&#x60; on the primary news feed. |  [optional] |




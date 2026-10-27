
# OverviewRuns

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **total** | **kotlin.Long** | Total number of runs at the resort. |  |
| **updatedAt** | [**java.time.OffsetDateTime**](java.time.OffsetDateTime.md) | When the most recent update to run status was made. |  |
| **&#x60;open&#x60;** | **kotlin.Long** | Number of runs currently open.  Not included if the runs status feature is disabled. |  [optional] |
| **groomed** | **kotlin.Long** | Number of runs groomed since the resort last closed (see &#x60;groomed_today&#x60;).  Not included if the runs grooming feature is disabled. |  [optional] |
| **openAcres** | **kotlin.Long** | Total acres of open runs.  Not included if acres are not tracked or the runs status feature is disabled. |  [optional] |
| **totalAcres** | **kotlin.Long** | Total acres of all runs.  Not included if acres are not tracked. |  [optional] |




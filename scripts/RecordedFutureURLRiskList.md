---
id: recorded-future-url-risk-list
title: Recorded Future URL Risk List
---

Extracts the URL risk list from the recorded future and creates indicators accordingly.

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | python |
| Tags | RecordedFuture |
| Demisto Version | 0.0.0 |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| list | Specifies a URL list by a risk rule name. This can be retrieved with the `get-url-riskrules` command. |
| threshold | The minimum threshold score to consider indicators as malicious (65-99, greater than or equal to). |
| delete_existing | Whether to delete the existing recorded future malicious URL indicators. |

## Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| InfoFile.Name | The name of the file. | string |
| InfoFile.EntryID | The entry ID of the file. | string |
| InfoFile.Size | The size of the file. | number |
| InfoFile.Type | The type of the file. For example, "PE". | string |
| InfoFile.Info | The basic information of the file. | string |
| InfoFile.Extension | The extension of the file. | string |

---
id: exists
title: Exists
---

Checks if a given value exists in the context. The script will return "no" for an empty arrays. This script should be used mostly with DQ and selectors.

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | javascript |
| Tags | Utility, Condition |
| Demisto Version | 0.0.0 |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| value | The value to check if it exists. It can handle arrays as well. |

## Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| True | Whether the given value exists in context. | Unknown |
| False | Whether the given value does not exist in context. | Unknown |

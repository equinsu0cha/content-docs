---
id: google-auth-url
title: Google Auth URL
---

Generates a Google authorized URL to authenticate a given list of scopes.

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | javascript |
| Tags | google apps |
| Demisto Version | 0.0.0 |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| scopes | The comma-separated list of scopes we will use with the token. |
| proxy | Whether to use the system proxy settings. |

## Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| GoogleAuth.URL | The newly generated URL for authentication. | Unknown |

---
id: retrieve-file-from-endpoint-generic
title: Retrieve File From Endpoint Generic
---

Retrieves file samples from an endpoint using the following playbooks:
- Get File Sample From Path - Generic
- Get File Sample By Hash - Generic v2

## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

### Sub-playbooks
* Get File Sample From Path - Generic
* Get File Sample By Hash - Generic v2

### Integrations
This playbook does not use any integrations.

### Scripts
This playbook does not use any scripts.

### Commands
This playbook does not use any commands.

## Playbook Inputs
---

| **Name** | **Description** | **Default Value** | **Source** | **Required** |
| --- | --- | --- | --- | --- |
| MD5 | Get file sample from MD5 hash input. | MD5 | File | Optional |
| SHA256 | Get file sample from SHA256 hash input. | SHA256 | File | Optional |
| Hostname | The hostname of the machine on which the file is located. | Hostname | Endpoint | Optional |
| Path | The file path. | Path | File | Optional |
| UseD2 | Whether a D2 agent will be used to retrieve the file. The default is "no". | no | - | Optional |

## Playbook Outputs
---
There are no outputs for this playbook.

![Retrieve_File_from_Endpoint_Generic](https://github.com/ElazarK/content-docs/blob/master/images/playbooks/Retrieve_File_from_Endpoint_Generic.png)

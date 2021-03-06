---
id: dedup-incidents-ml
title: DeDup Incidents ML
---

Checks for duplicate incidents of the current incident, and closes it if a duplicate has been found. This is accomplished though the `machine-learning find duplicates` automation.

## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

## Sub-playbooks
This playbook does not use any sub-playbooks.

## Integrations
This playbook does not use any integrations.

## Scripts
* GetDuplicatesMlv2
* Print
* CloseInvestigationAsDuplicate

## Commands
This playbook does not use any commands.

## Playbook Inputs
---

| **Name** | **Description** | **Default Value** | **Required** |
| --- | --- | --- | --- |
| closeThreshold | The candidate with a score above the threshold will close the investigation automatically, and mark it as a duplicate to the current incident. | 0.75 | Required |

## Playbook Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| foundDuplicates | Whether any duplicate incidents were found. | boolean |
| duplicateCandidate | The duplicate top candidate. | unknown |

![DeDup_incidents_ML](https://github.com/ElazarK/content-docs/blob/master/images/playbooks/DeDup_incidents_-_ML.png)

---
id: calculate-severity-by-highest-dbotScore
title: Calculate Severity by Highest DBotScore
---

Calculates the incident severity level according to the highest indicator DBotScore.

## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

## Sub-playbooks
This playbook does not use any sub-playbooks.

## Integrations
This playbook does not use any integrations.

## Scripts
* Set

## Commands
This playbook does not use any commands.

## Playbook Inputs
---

| **Name** | **Description** | **Default Value** | **Source** | **Required** |
| --- | --- | --- | --- | --- |
| DBotScore | The array of all indicators associated with the incident.  | None | DBotScore | Optional |

## Playbook Outputs
---

| **Path** | **Description** | **Type** |
| --- | --- | --- |
| Severities.DBotScoreSeverity | The severity level of the incident identified and set in the Calculate Severity By Highest DBotScore playbook. | string |

![Calculate_Severity_By_Highest_DBotScore](https://github.com/ElazarK/content-docs/blob/master/images/playbooks/Calculate_Severity_By_Highest_DBotScore.png)

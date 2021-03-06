---
id: get-original-email-ews
title: Get Original Email EWS
---

Gets emails from specific folders and pre-process them using EWS. 

## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

### Sub-playbooks
This playbook does not use any sub-playbooks.

### Integrations
This playbook does not use any integrations.

### Scripts
* DBotPreProcessTextData
* FileToBase64List
* GetEWSFolder

### Commands
This playbook does not use any commands.

## Playbook Inputs
---

| **Name** | **Description** | **Default Value** | **Required** |
| --- | --- | --- | --- |
| foldersPathsGlobal | A comma-separated list of folder paths from the Inbox. For example: inbox,inboxfolder | inbox,inbox\TESTATTACH | Required |
| listName | The name of the list in which mails will be saved. | - | Required |
| limit | The maximum number of emails to fetch from each folder. | 10 | Optional |

## Playbook Outputs
---
There are no outputs for this playbook.

![Get_Original_Email_EWS](https://github.com/ElazarK/content-docs/blob/master/images/playbooks/Get_Original_Email_EWS.png)

---
id: search-and-delete-emails-generic
title: Search and Delete Emails Generic
---

Searches and deletes emails with similar attributes of a malicious email.

## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

### Sub-playbooks
* Search And Delete Emails - EWS

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
| From | The value of the malicious email's "From" attribute. | emailfrom | incident | Optional |
| Subject | The value of the malicious email's "Subject" attribute. | emailsubject | incident | Optional |
| AttachmentName | The value of the malicious email's "AttachmentName" attribute. | attachmentname | incident | Optional |

## Playbook Outputs
---
There are no outputs for this playbook.

![Search_And_Delete_Emails_Generic](https://github.com/ElazarK/content-docs/blob/master/images/playbooks/Search_And_Delete_Emails_Generic.png)

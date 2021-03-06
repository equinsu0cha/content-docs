---
id: pan-os-block--ip-static-address-group
title: PAN-OS Block IP Static Address Group
---

Blocks IP addresses using Static Address Groups in Palo Alto Networks Panorama or Firewall.
The playbook receives malicious IP addresses and an address group name as inputs, verifies that the addresses are not already a part of the address group, adds them and commits the configuration.

**Note**: The playbook does not block the address group communication using a policy block rule. This step will be taken once outside of the playbook.

## Dependencies
This playbook uses the following sub-playbooks, integrations, and scripts.

### Sub-playbooks
* PAN-OS Commit Configuration

### Integrations
This playbook does not use any integrations.

### Scripts
This playbook does not use any scripts.

### Commands
* panorama-create-address
* panorama-edit-address-group
* panorama-get-address-group

## Playbook Inputs
---

| **Name** | **Description** | **Default Value** | **Source** | **Required** |
| --- | --- | --- | --- | --- |
| IP | The IP address to block. | Address | IP | Optional |
| LogForwarding | The Panorama log forwarding object name. | - | - | Optional |
| AddressGroupName | The static address group name. | Demisto Remediation - Static Address Group | - | Optional |
| AutoCommit | Whether to commit the configuration automatically. "Yes" will commit automatically. "No" will commit manually. | No | - | Optional |

## Playbook Outputs
---
There are no outputs for this playbook.

![PAN-OS_Block_IP_Static_Address_Group](https://github.com/ElazarK/content-docs/blob/master/images/playbooks/PAN-OS_Block_IP_Static_Address_Group.png)

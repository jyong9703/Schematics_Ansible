# Classic VSI Power Actions (Schematics)

This repository provides two Ansible playbooks to manage IBM Cloud Classic Virtual Server Instances
using SoftLayer API to start and stop instances.

## Playbooks

- **start-vsi-playbook.yml** : Start Classic VSI
- **stop-vsi-playbook.yml** : Stop Classic VSI

## Required Variables

| Variable | Description |
|----------|-------------|
| classic_username | Classic Infrastructure username |
| classic_api_key | Classic Infrastructure API key |
| vsi_id | Virtual Server ID |

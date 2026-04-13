# Proxmox Collection

## Roles

### proxmox_template

Creates a cloud-init enabled Proxmox template.

### proxmox_vm

Clones and configures VMs from template.

## Example

```yaml
- hosts: localhost
  roles:
    - ralphpy.proxmox.proxmox_template
    - ralphpy.proxmox.proxmox_vm

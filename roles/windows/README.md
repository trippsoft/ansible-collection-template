<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.template.windows
Version: 1.3.0

This role seals a Windows machine for use as a template.

## Requirements

| Platform | Versions |
| -------- | -------- |
| Windows | <ul><li>all</li></ul> |

## Dependencies

| Collection |
| ---------- |
| ansible.windows |
| community.windows |

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| win_is_vagrant | <p>Whether the machine is to be used as a Vagrant box.</p> | bool | no |  | False |
| win_target_hostname | <p>The hostname to set on the machine.</p><p>This is only used if the machine is a Vagrant box.</p> | str | no |  |  |
| win_set_sshd_manual | <p>Whether to set the OpenSSH service to Manual.</p> | bool | no |  | False |
| win_add_ssh_trusted_ca_cert | <p>Whether to install an SSH trusted CA certificate.</p> | bool | no |  | False |
| win_ssh_trusted_ca_cert_path | <p>The path to the SSH trusted CA certificate.</p><p>This is only used if an SSH trusted CA certificate is to be installed.</p> | str | no |  |  |
| win_ssl_ca_certs | <p>A list of SSL CA certificates to install.</p> | list of '' | no |  | [] |
| win_use_bleachbit | <p>Whether to use BleachBit to clean up the machine.</p> | bool | no |  | True |
| win_disable_mouse_acceleration | <p>Whether to disable mouse acceleration.</p> | bool | no |  | True |
| win_remove_appx_packages_for_sysprep | <p>Whether to remove AppX packages to allow for sysprep.</p> | bool | no |  | True |


## License
MIT

## Author and Project Information
Jim Tarpley (@trippsc2)
<!-- END_ANSIBLE_DOCS -->

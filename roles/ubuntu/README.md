<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.template.ubuntu
Version: 1.4.0

This role seals an Ubuntu machine for use as a template.

## Requirements

| Platform | Versions |
| -------- | -------- |
| Ubuntu | <ul><li>noble</li><li>jammy</li></ul> |

## Dependencies

None.

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| ubuntu_target_hostname | <p>The target hostname.</p> | str | yes |  |  |
| ubuntu_add_ssh_trusted_ca_cert | <p>Whether to add a SSH trusted CA certificate.</p> | bool | no |  | False |
| ubuntu_ssh_trusted_ca_cert_path | <p>The path to the SSH trusted CA certificate.</p><p>Only needed if *ubuntu_add_ssh_trusted_ca_cert* is `true`.</p> | path | no |  |  |
| ubuntu_ssl_ca_certificates | <p>List of trusted SSL CA certificates to add.</p> | list of '' | no |  | [] |
| ubuntu_install_cloud_init | <p>Whether to install cloud-init.</p><p>This is needed for VMware and Nutanix templates.</p> | bool | no |  | False |


## License
MIT

## Author and Project Information
Jim Tarpley (@trippsc2)
<!-- END_ANSIBLE_DOCS -->

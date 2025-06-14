<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.template.rhel
Version: 1.3.1

This role seals a RHEL-based machine for use as a template.

## Requirements

| Platform | Versions |
| -------- | -------- |
| EL | <ul><li>9</li><li>8</li></ul> |

## Dependencies

None.

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| rhel_target_hostname | <p>The target hostname.</p> | str | yes |  |  |
| rhel_add_ssh_trusted_ca_cert | <p>Whether to add a SSH trusted CA certificate.</p> | bool | no |  | False |
| rhel_ssh_trusted_ca_cert_path | <p>The path to the SSH trusted CA certificate.</p><p>Only needed if `rhel_add_ssh_trusted_ca_cert` is `true`.</p> | path | no |  |  |
| rhel_ssl_ca_certificates | <p>List of trusted SSL CA certificates to add.</p> | list of '' | no |  | [] |
| rhel_install_cloud_init | <p>Whether to install cloud-init.</p><p>This is needed for VMware and Nutanix templates.</p> | bool | no |  | False |


## License
MIT

## Author and Project Information
Jim Tarpley (@trippsc2)
<!-- END_ANSIBLE_DOCS -->

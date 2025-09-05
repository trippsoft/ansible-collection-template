<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.template.debian
Version: 1.4.0

This role seals a Debian machine for use as a template.

## Requirements

| Platform | Versions |
| -------- | -------- |
| Debian | <ul><li>bookworm</li></ul> |

## Dependencies

None.

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| debian_target_hostname | <p>The target hostname.</p> | str | yes |  |  |
| debian_add_ssh_trusted_ca_cert | <p>Whether to add a SSH trusted CA certificate.</p> | bool | no |  | False |
| debian_ssh_trusted_ca_cert_path | <p>The path to the SSH trusted CA certificate.</p><p>Only needed if `debian_add_ssh_trusted_ca_cert` is `true`.</p> | path | no |  |  |
| debian_ssl_ca_certificates | <p>List of trusted SSL CA certificates to add.</p> | list of '' | no |  | [] |
| debian_install_cloud_init | <p>Whether to install cloud-init.</p><p>This is needed for VMware and Nutanix templates.</p> | bool | no |  | False |


## License
MIT

## Author and Project Information
Jim Tarpley (@trippsc2)
<!-- END_ANSIBLE_DOCS -->

<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.template.bleachbit
Version: 1.3.0

This role runs Bleachbit from a portable executable on Windows systems.

## Requirements

| Platform | Versions |
| -------- | -------- |
| Windows | <ul><li>2019</li><li>2022</li></ul> |

## Dependencies

| Collection |
| ---------- |
| ansible.windows |
| chocolatey.chocolatey |

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| bleachbit_options | <p>List of BleachBit options to clean.</p><p>See https://docs.bleachbit.org/doc/cleanerml.html for a list of available options.</p> | list of 'str' | no |  | ['deepscan.backup', 'deepscan.ds_store', 'deepscan.thumbs_db', 'deepscan.tmp', 'deepscan.vim_swap_root', 'deepscan.vim_swap_user', 'internet_explorer.cache', 'internet_explorer.cookies', 'internet_explorer.downloads', 'internet_explorer.forms', 'internet_explorer.history', 'internet_explorer.logs', 'microsoft_edge.cache', 'microsoft_edge.cookies', 'microsoft_edge.dom', 'microsoft_edge.form_history', 'microsoft_edge.history', 'microsoft_edge.passwords', 'microsoft_edge.search_engines', 'microsoft_edge.session', 'microsoft_edge.site_preferences', 'microsoft_edge.vacuum', 'paint.mru', 'system.clipboard', 'system.logs', 'system.memory_dump', 'system.muicache', 'system.prefetch', 'system.recycle_bin', 'system.tmp', 'system.updates', 'windows_defender.backup', 'windows_defender.history', 'windows_defender.logs', 'windows_defender.quarantine', 'windows_defender.temp', 'windows_explorer.mru', 'windows_explorer.recent_documents', 'windows_explorer.run', 'windows_explorer.search_history', 'windows_explorer.shellbags', 'windows_explorer.thumbnails', 'windows_media_player.cache', 'windows_media_player.mru', 'wordpad.mru'] |


## License
MIT

## Author and Project Information
Jim Tarpley (@trippsc2)
<!-- END_ANSIBLE_DOCS -->

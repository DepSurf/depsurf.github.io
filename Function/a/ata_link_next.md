# Function: <code>ata_link_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584906992,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:194",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_do_set_mode"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906992,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585297146,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:197",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_do_set_mode"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585270544,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585496932,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:197",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_do_set_mode"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470080,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585553792,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:197",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585553792,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585985472,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:197",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585985472,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233824,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:197",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586233824,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586374240,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:197",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586374240,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586617824,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586617824,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586765488,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586765488,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587577868,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:180",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_dev_xfermask"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_eh_unload",
        "drivers/ata/libata-eh.c:ata_eh_unload",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587570448,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587644124,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:180",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_dev_xfermask"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_eh_unload",
        "drivers/ata/libata-eh.c:ata_eh_unload",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587636848,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587520966,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:180",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_dev_xfermask"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517552,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588097000,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:186",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-core.c:ata_dev_xfermask"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093680,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589475096,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:187",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-core.c:ata_dev_xfermask"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589470848,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591055608,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:187",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-core.c:ata_dev_xfermask"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591049280,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591411541,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:187",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-core.c:ata_dev_xfermask"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591412384,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591762821,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:187",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-core.c:ata_dev_xfermask",
        "drivers/ata/libata-core.c:ata_dev_xfermask"
      ],
      "caller_func": [
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_resume",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_do_eh",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_eh_unload",
        "drivers/ata/libata-eh.c:ata_eh_unload",
        "drivers/ata/libata-eh.c:ata_eh_unload",
        "drivers/ata/libata-eh.c:ata_eh_unload",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-pmp.c:sata_pmp_quirks",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591764496,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499685120,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_led_show",
        "drivers/ata/libahci.c:ahci_led_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499685120,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232132544,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_port_resume",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_error_intr",
        "drivers/ata/libahci.c:ahci_led_show",
        "drivers/ata/libahci.c:ahci_led_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232132544,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293014832,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293014832,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276856398,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276856398,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586524224,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586524224,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586392800,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586392800,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720048,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720048,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ata_link * ata_link_next(struct ata_link * link, struct ata_port * ap, enum ata_link_iter_mode mode)
```

```json
{
  "name": "ata_link_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586826224,
      "name": "ata_link_next",
      "external": true,
      "loc": "drivers/ata/libata-core.c:181",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_runtime_idle",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_detach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-pmp.c:sata_pmp_attach",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826224,
      "name": "ata_link_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

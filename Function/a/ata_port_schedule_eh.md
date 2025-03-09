# Function: <code>ata_port_schedule_eh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584960237,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1042",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963232,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585330962,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1042",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585330432,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585532002,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1042",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585531472,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585618114,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1043",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585617536,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586049842,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:1041",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586049248,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586297650,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:992",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586297072,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586439170,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:988",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586438592,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586683757,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586683168,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586830797,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586830208,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587633442,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:970",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_do_link_abort"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587626672,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587694406,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:970",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_do_link_abort"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587687632,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587573606,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:970",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_do_link_abort"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587566800,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588155350,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:978",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_do_link_abort"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588147328,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589535980,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:975",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_do_link_abort"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589529296,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591126524,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:977",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_do_link_abort"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591116032,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591483820,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:980",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_do_link_abort"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591473824,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591832580,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:998",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_handle_port_suspend",
        "drivers/ata/libata-eh.c:ata_do_link_abort"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591822112,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499760704,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499759904,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232205648,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232204948,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293105920,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293105088,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276918112,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276917522,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586589373,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586588784,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586457885,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457296,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586785357,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586784768,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void ata_port_schedule_eh(struct ata_port * ap)
```

```json
{
  "name": "ata_port_schedule_eh",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586891405,
      "name": "ata_port_schedule_eh",
      "external": true,
      "loc": "drivers/ata/libata-eh.c:971",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_do_link_abort",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:__ata_port_probe",
        "drivers/ata/libata-core.c:ata_port_request_pm",
        "drivers/ata/libata-core.c:ata_qc_complete",
        "drivers/ata/libata-scsi.c:ata_scsi_user_scan",
        "drivers/ata/libata-scsi.c:ata_scsi_slave_destroy",
        "drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity",
        "drivers/ata/libata-scsi.c:ata_ncq_prio_enable_store",
        "drivers/ata/libata-scsi.c:ata_scsi_park_store",
        "drivers/ata/libata-scsi.c:ata_scsi_lpm_store",
        "drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586890816,
      "name": "ata_port_schedule_eh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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

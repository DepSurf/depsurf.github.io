# Function: <code>ata_port_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912064,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6812",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_drain_fifo",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912064,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585274448,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7016",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_drain_fifo",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274448,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474000,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7058",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_drain_fifo",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474000,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585557488,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7144",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557488,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585989200,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7174",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989200,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586262562,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7221",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586262562,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586403026,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7225",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403026,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586647233,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7210",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586647233,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586794687,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7257",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794687,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587598135,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6434",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sata.c:ata_qc_complete_multiple",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587598135,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591522122,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6434",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sata.c:ata_qc_complete_multiple",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591522122,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591464082,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6434",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sata.c:ata_qc_complete_multiple",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591464082,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592531259,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6496",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sata.c:ata_qc_complete_multiple",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592531259,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499721936,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7257",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libahci.c:ahci_port_stop",
        "drivers/ata/libahci.c:ahci_port_suspend",
        "drivers/ata/libahci.c:ahci_read_em_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499721936,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232168944,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7257",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libahci.c:ahci_port_stop",
        "drivers/ata/libahci.c:ahci_port_suspend",
        "drivers/ata/libahci.c:ahci_read_em_buffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232168944,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293058264,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7257",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293058264,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276886404,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7257",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276886404,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553295,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7257",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553295,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586421871,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7257",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586421871,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586749247,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7257",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586749247,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_port_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586855311,
      "name": "ata_port_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7257",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_host_register",
        "drivers/ata/libata-core.c:ata_qc_complete_multiple",
        "drivers/ata/libata-core.c:ata_force_cbl",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_lost_interrupt",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-sff.c:ata_sff_busy_sleep",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_stm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm",
        "drivers/ata/libata-acpi.c:ata_acpi_gtm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855311,
      "name": "ata_port_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void ata_port_printk(const struct ata_port * ap, const char * level, const char * fmt, void (anon))
```
</details>
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

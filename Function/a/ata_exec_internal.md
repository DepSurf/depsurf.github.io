# Function: <code>ata_exec_internal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584922768,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1736",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_do_set_mode"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron",
        "drivers/ata/libata-zpodd.c:zpodd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584922768,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585285574,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1739",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585285216,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585485158,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1748",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585484800,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585569826,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1748",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585568192,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586001522,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1748",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585999888,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586248326,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1739",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586247264,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586388790,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1739",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586387728,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586633306,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586648314,
      "name": "ata_exec_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586631376,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586780874,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586778944,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587585750,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1667",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron",
        "drivers/ata/libata-zpodd.c:zpodd_get_mech_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587584624,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587651926,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1667",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron",
        "drivers/ata/libata-zpodd.c:zpodd_get_mech_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587650784,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587530902,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1667",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530624,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588108518,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1670",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588108240,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589487290,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1645",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_set_max_sectors"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:ata_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589486528,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591068874,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1645",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_set_max_sectors"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:ata_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068000,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591424362,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1679",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_set_max_sectors"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:ata_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591423488,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591776698,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1674",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_power_set_active",
        "drivers/ata/libata-core.c:ata_dev_power_set_standby",
        "drivers/ata/libata-core.c:ata_dev_power_is_active",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_set_max_sectors"
      ],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_maybe_retry_flush",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:ata_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591774880,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499705252,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499702784,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232150432,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-core.c:ata_dev_read_id"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232149052,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293037852,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293034992,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276871946,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-pmp.c:sata_pmp_write",
        "drivers/ata/libata-pmp.c:sata_pmp_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276870086,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586539530,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537600,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586408106,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586406176,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586735434,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586733504,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
unsigned int ata_exec_internal(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, void * buf, unsigned int buflen, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586841498,
      "name": "ata_exec_internal",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1723",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_park_issue_cmd",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:atapi_eh_request_sense",
        "drivers/ata/libata-eh.c:atapi_eh_tur",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-zpodd.c:zpodd_init",
        "drivers/ata/libata-zpodd.c:zpodd_post_poweron"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586839568,
      "name": "ata_exec_internal",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int timeout</code> ➡️ <code>unsigned int timeout</code>
</li>
</ul>
</details>
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

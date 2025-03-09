# Function: <code>sectors_to_logical</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585432951,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_unlock_zone",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_write_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585497944,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:187",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518182,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:187",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_write_unlock_zone",
        "drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585939448,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:188",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585949891,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:188",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_write_unlock_zone",
        "drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586186608,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:187",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586196670,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:187",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_report_cmnd"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586329408,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586338456,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586572687,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586581752,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586720047,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586729113,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
sector_t sectors_to_logical(struct scsi_device * sdev, sector_t sector)
```

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587504352,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:192",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd"
      ]
    },
    {
      "addr": 18446744071587529728,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:192",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587504352,
      "name": "sectors_to_logical",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587529728,
      "name": "sectors_to_logical",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587574388,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:195",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_zeroes_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587600034,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:195",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587458196,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:195",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587480482,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:195",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588037769,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:195",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588056287,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:195",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
sector_t sectors_to_logical(struct scsi_device * sdev, sector_t sector)
```

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589400332,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:220",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589421631,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:220",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
      ],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589416688,
      "name": "sectors_to_logical",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071594401264,
      "name": "sectors_to_logical.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
sector_t sectors_to_logical(struct scsi_device * sdev, sector_t sector)
```

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590973820,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:220",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590998031,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:220",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
      ],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590992688,
      "name": "sectors_to_logical",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071596261221,
      "name": "sectors_to_logical.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
sector_t sectors_to_logical(struct scsi_device * sdev, sector_t sector)
```

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591327404,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:220",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591351727,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:220",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
      ],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591346384,
      "name": "sectors_to_logical",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071596789446,
      "name": "sectors_to_logical.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
sector_t sectors_to_logical(struct scsi_device * sdev, sector_t sector)
```

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591676956,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:221",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591701679,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:221",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
      ],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591696272,
      "name": "sectors_to_logical",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071597698526,
      "name": "sectors_to_logical.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499631484,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499640492,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232085668,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 3232095220,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292950292,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292962208,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276813854,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276823674,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586410527,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586419593,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586286783,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586295849,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586674607,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586683673,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sectors_to_logical",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586780623,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_completed_bytes",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586789705,
      "name": "sectors_to_logical",
      "external": false,
      "loc": "drivers/scsi/sd.h:186",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
sector_t sectors_to_logical(struct scsi_device * sdev, sector_t sector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
sector_t sectors_to_logical(struct scsi_device * sdev, sector_t sector)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
sector_t sectors_to_logical(struct scsi_device * sdev, sector_t sector)
```
</details>
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

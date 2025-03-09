# Function: <code>logical_to_sectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "logical_to_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584865379,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.c:2815",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "logical_to_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585229563,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:149",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585424813,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:161",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585434615,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:161",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_write_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete"
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585509667,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:172",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518886,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:172",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete"
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585941429,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:173",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585950588,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:173",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_write_lock_zone",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete"
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586188500,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:172",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586197470,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:172",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete"
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586332072,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586339364,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586574280,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586582563,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586721710,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586729955,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
sector_t logical_to_sectors(struct scsi_device * sdev, sector_t blocks)
```

```json
{
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587504384,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:177",
      "file": "drivers/scsi/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ]
    },
    {
      "addr": 18446744071587529696,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:177",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_capacity",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587504384,
      "name": "logical_to_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587529696,
      "name": "logical_to_sectors",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587575363,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:180",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587601039,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:180",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_capacity",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587459171,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:180",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587482374,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:180",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588032401,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:180",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588058236,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:180",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589399844,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:205",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_cpr",
        "drivers/scsi/sd.c:sd_read_cpr",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589422810,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:205",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590973311,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:205",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_cpr",
        "drivers/scsi/sd.c:sd_read_cpr",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590999274,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:205",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591324152,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:205",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_cpr",
        "drivers/scsi/sd.c:sd_read_cpr",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591352914,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:205",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591676424,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:206",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_read_cpr",
        "drivers/scsi/sd.c:sd_read_cpr",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591702912,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:206",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_zone_wp_update",
        "drivers/scsi/sd_zbc.c:sd_zbc_cmnd_checks",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report",
        "drivers/scsi/sd_zbc.c:sd_zbc_parse_report"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499633004,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499641124,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232087132,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 3232095972,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292952220,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292962928,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276815194,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276824500,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586412190,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586420435,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586288446,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586296691,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586676270,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586684515,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
  "name": "logical_to_sectors",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586782286,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_getgeo",
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586790547,
      "name": "logical_to_sectors",
      "external": false,
      "loc": "drivers/scsi/sd.h:171",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_reset_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones",
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
sector_t logical_to_sectors(struct scsi_device * sdev, sector_t blocks)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
sector_t logical_to_sectors(struct scsi_device * sdev, sector_t blocks)
```
</details>
</li>
</ul>

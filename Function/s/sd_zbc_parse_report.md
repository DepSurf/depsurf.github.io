# Function: <code>sd_zbc_parse_report</code>

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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585432198,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:61",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585516776,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:61",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585948488,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:42",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586196096,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:42",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586338157,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:42",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586581458,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586728818,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int sd_zbc_parse_report(struct scsi_disk * sdkp, u8 * buf, unsigned int idx, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587529760,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:47",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587529760,
      "name": "sd_zbc_parse_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int sd_zbc_parse_report(struct scsi_disk * sdkp, u8 * buf, unsigned int idx, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587596592,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:47",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587596592,
      "name": "sd_zbc_parse_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int sd_zbc_parse_report(struct scsi_disk * sdkp, u8 * buf, unsigned int idx, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587477680,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:47",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587477680,
      "name": "sd_zbc_parse_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_parse_report(struct scsi_disk * sdkp, u8 * buf, unsigned int idx, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:47",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053872,
      "name": "sd_zbc_parse_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    },
    {
      "addr": 18446744071592529918,
      "name": "sd_zbc_parse_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_parse_report(struct scsi_disk * sdkp, const u8 * buf, unsigned int idx, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:73",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589419104,
      "name": "sd_zbc_parse_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
    },
    {
      "addr": 18446744071594401543,
      "name": "sd_zbc_parse_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_parse_report(struct scsi_disk * sdkp, const u8 * buf, unsigned int idx, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:76",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590995328,
      "name": "sd_zbc_parse_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
    },
    {
      "addr": 18446744071596261500,
      "name": "sd_zbc_parse_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_parse_report(struct scsi_disk * sdkp, const u8 * buf, unsigned int idx, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:76",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591349008,
      "name": "sd_zbc_parse_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
    },
    {
      "addr": 18446744071596789704,
      "name": "sd_zbc_parse_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_zbc_parse_report(struct scsi_disk * sdkp, const u8 * buf, unsigned int idx, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:76",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591698912,
      "name": "sd_zbc_parse_report",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
    },
    {
      "addr": 18446744071597698829,
      "name": "sd_zbc_parse_report.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499640140,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232094800,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292961712,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276822906,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586419298,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586295554,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586683378,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "sd_zbc_parse_report",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586789410,
      "name": "sd_zbc_parse_report",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:30",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
int sd_zbc_parse_report(struct scsi_disk * sdkp, u8 * buf, unsigned int idx, report_zones_cb cb, void * data)
```
</details>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 * buf</code> ➡️ <code>const u8 * buf</code>
</li>
</ul>
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

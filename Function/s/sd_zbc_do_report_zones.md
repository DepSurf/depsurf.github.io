# Function: <code>sd_zbc_do_report_zones</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586337424,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:78",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586337424,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586580736,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586580736,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586728096,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586728096,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587530112,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:92",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_check_capacity",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530112,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587596912,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:93",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_check_capacity",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587596912,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587478000,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:93",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587478000,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588053184,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:93",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053184,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589416736,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:141",
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
      "addr": 18446744071589416736,
      "name": "sd_zbc_do_report_zones",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590992752,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:144",
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
      "addr": 18446744071590992752,
      "name": "sd_zbc_do_report_zones",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591346448,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:144",
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
      "addr": 18446744071591346448,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591696336,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:144",
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
      "addr": 18446744071591696336,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499638400,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499638400,
      "name": "sd_zbc_do_report_zones.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232092960,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232092960,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292959680,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292959680,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276821084,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_check_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276821084,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586418576,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586418576,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586294832,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586294832,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586682656,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586682656,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```

```json
{
  "name": "sd_zbc_do_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586788688,
      "name": "sd_zbc_do_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:66",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_report_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586788688,
      "name": "sd_zbc_do_report_zones",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk * sdkp, unsigned char * buf, unsigned int buflen, sector_t lba, bool partial)
```
</details>
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

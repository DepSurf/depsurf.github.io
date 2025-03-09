# Function: <code>sd_zbc_zone_wp_update</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd * cmd, unsigned int good_bytes)
```

```json
{
  "name": "sd_zbc_zone_wp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587531504,
      "name": "sd_zbc_zone_wp_update",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:439",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531504,
      "name": "sd_zbc_zone_wp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd * cmd, unsigned int good_bytes)
```

```json
{
  "name": "sd_zbc_zone_wp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587598272,
      "name": "sd_zbc_zone_wp_update",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:440",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587598272,
      "name": "sd_zbc_zone_wp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 481
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
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd * cmd, unsigned int good_bytes)
```

```json
{
  "name": "sd_zbc_zone_wp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587478688,
      "name": "sd_zbc_zone_wp_update",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:442",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587478688,
      "name": "sd_zbc_zone_wp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
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
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd * cmd, unsigned int good_bytes)
```

```json
{
  "name": "sd_zbc_zone_wp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_zone_wp_update",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:441",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588054496,
      "name": "sd_zbc_zone_wp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
    },
    {
      "addr": 18446744071592530093,
      "name": "sd_zbc_zone_wp_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd * cmd, unsigned int good_bytes)
```

```json
{
  "name": "sd_zbc_zone_wp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_zone_wp_update",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:525",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418560,
      "name": "sd_zbc_zone_wp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071594401440,
      "name": "sd_zbc_zone_wp_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd * cmd, unsigned int good_bytes)
```

```json
{
  "name": "sd_zbc_zone_wp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_zone_wp_update",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:529",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590994032,
      "name": "sd_zbc_zone_wp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 648
    },
    {
      "addr": 18446744071596261354,
      "name": "sd_zbc_zone_wp_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd * cmd, unsigned int good_bytes)
```

```json
{
  "name": "sd_zbc_zone_wp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_zone_wp_update",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:531",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591348336,
      "name": "sd_zbc_zone_wp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071596789610,
      "name": "sd_zbc_zone_wp_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd * cmd, unsigned int good_bytes)
```

```json
{
  "name": "sd_zbc_zone_wp_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_zone_wp_update",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:531",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591698224,
      "name": "sd_zbc_zone_wp_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071597698690,
      "name": "sd_zbc_zone_wp_update.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
unsigned int sd_zbc_zone_wp_update(struct scsi_cmnd * cmd, unsigned int good_bytes)
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

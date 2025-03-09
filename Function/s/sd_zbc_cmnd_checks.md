# Function: <code>sd_zbc_cmnd_checks</code>

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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_zbc_cmnd_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587532048,
      "name": "sd_zbc_cmnd_checks",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:244",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532048,
      "name": "sd_zbc_cmnd_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_zbc_cmnd_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587598848,
      "name": "sd_zbc_cmnd_checks",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:245",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587598848,
      "name": "sd_zbc_cmnd_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_zbc_cmnd_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587479264,
      "name": "sd_zbc_cmnd_checks",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:245",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479264,
      "name": "sd_zbc_cmnd_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_zbc_cmnd_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_cmnd_checks",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:244",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053728,
      "name": "sd_zbc_cmnd_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071592529882,
      "name": "sd_zbc_cmnd_checks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_zbc_cmnd_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_cmnd_checks",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:325",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589417264,
      "name": "sd_zbc_cmnd_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071594401318,
      "name": "sd_zbc_cmnd_checks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_zbc_cmnd_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_cmnd_checks",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:328",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590993312,
      "name": "sd_zbc_cmnd_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071596261275,
      "name": "sd_zbc_cmnd_checks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_zbc_cmnd_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_cmnd_checks",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:330",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591347040,
      "name": "sd_zbc_cmnd_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071596789500,
      "name": "sd_zbc_cmnd_checks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd * cmd)
```

```json
{
  "name": "sd_zbc_cmnd_checks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_cmnd_checks",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:330",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_setup_zone_mgmt_cmnd",
        "drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591696928,
      "name": "sd_zbc_cmnd_checks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071597698580,
      "name": "sd_zbc_cmnd_checks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
blk_status_t sd_zbc_cmnd_checks(struct scsi_cmnd * cmd)
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

# Function: <code>sd_zbc_setup_zone_mgmt_cmnd</code>

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
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd * cmd, unsigned char op, bool all)
```

```json
{
  "name": "sd_zbc_setup_zone_mgmt_cmnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587533776,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:384",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587533776,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd * cmd, unsigned char op, bool all)
```

```json
{
  "name": "sd_zbc_setup_zone_mgmt_cmnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587600016,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:385",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587600016,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd * cmd, unsigned char op, bool all)
```

```json
{
  "name": "sd_zbc_setup_zone_mgmt_cmnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587480464,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:387",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587480464,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd * cmd, unsigned char op, bool all)
```

```json
{
  "name": "sd_zbc_setup_zone_mgmt_cmnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:386",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592530442,
      "name": "sd_zbc_setup_zone_mgmt_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588056240,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd * cmd, unsigned char op, bool all)
```

```json
{
  "name": "sd_zbc_setup_zone_mgmt_cmnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:471",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594402116,
      "name": "sd_zbc_setup_zone_mgmt_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071589421584,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd * cmd, unsigned char op, bool all)
```

```json
{
  "name": "sd_zbc_setup_zone_mgmt_cmnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:475",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596262065,
      "name": "sd_zbc_setup_zone_mgmt_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071590997984,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd * cmd, unsigned char op, bool all)
```

```json
{
  "name": "sd_zbc_setup_zone_mgmt_cmnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:477",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596790261,
      "name": "sd_zbc_setup_zone_mgmt_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071591351680,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd * cmd, unsigned char op, bool all)
```

```json
{
  "name": "sd_zbc_setup_zone_mgmt_cmnd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:477",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_init_command"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597699499,
      "name": "sd_zbc_setup_zone_mgmt_cmnd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071591701632,
      "name": "sd_zbc_setup_zone_mgmt_cmnd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
blk_status_t sd_zbc_setup_zone_mgmt_cmnd(struct scsi_cmnd * cmd, unsigned char op, bool all)
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

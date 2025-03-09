# Function: <code>sd_zbc_prepare_zone_append</code>

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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd * cmd, sector_t * lba, unsigned int nr_blocks)
```

```json
{
  "name": "sd_zbc_prepare_zone_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587533376,
      "name": "sd_zbc_prepare_zone_append",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:320",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587533376,
      "name": "sd_zbc_prepare_zone_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd * cmd, sector_t * lba, unsigned int nr_blocks)
```

```json
{
  "name": "sd_zbc_prepare_zone_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587599584,
      "name": "sd_zbc_prepare_zone_append",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:321",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587599584,
      "name": "sd_zbc_prepare_zone_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd * cmd, sector_t * lba, unsigned int nr_blocks)
```

```json
{
  "name": "sd_zbc_prepare_zone_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587480000,
      "name": "sd_zbc_prepare_zone_append",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:322",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587480000,
      "name": "sd_zbc_prepare_zone_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd * cmd, sector_t * lba, unsigned int nr_blocks)
```

```json
{
  "name": "sd_zbc_prepare_zone_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_prepare_zone_append",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:321",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592530323,
      "name": "sd_zbc_prepare_zone_append.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588055712,
      "name": "sd_zbc_prepare_zone_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd * cmd, sector_t * lba, unsigned int nr_blocks)
```

```json
{
  "name": "sd_zbc_prepare_zone_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_prepare_zone_append",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:406",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594402005,
      "name": "sd_zbc_prepare_zone_append.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071589421056,
      "name": "sd_zbc_prepare_zone_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd * cmd, sector_t * lba, unsigned int nr_blocks)
```

```json
{
  "name": "sd_zbc_prepare_zone_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_prepare_zone_append",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:409",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596261962,
      "name": "sd_zbc_prepare_zone_append.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071590997328,
      "name": "sd_zbc_prepare_zone_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd * cmd, sector_t * lba, unsigned int nr_blocks)
```

```json
{
  "name": "sd_zbc_prepare_zone_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_prepare_zone_append",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:411",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596790158,
      "name": "sd_zbc_prepare_zone_append.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071591351024,
      "name": "sd_zbc_prepare_zone_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 633
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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd * cmd, sector_t * lba, unsigned int nr_blocks)
```

```json
{
  "name": "sd_zbc_prepare_zone_append",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_prepare_zone_append",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:411",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_setup_read_write_cmnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597699283,
      "name": "sd_zbc_prepare_zone_append.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071591700928,
      "name": "sd_zbc_prepare_zone_append",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
blk_status_t sd_zbc_prepare_zone_append(struct scsi_cmnd * cmd, sector_t * lba, unsigned int nr_blocks)
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

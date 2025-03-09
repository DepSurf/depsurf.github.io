# Function: <code>sd_zbc_report_zones</code>

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
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585431536,
      "name": "sd_zbc_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:87",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431536,
      "name": "sd_zbc_report_zones.isra.9",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585516176,
      "name": "sd_zbc_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:87",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585516176,
      "name": "sd_zbc_report_zones.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585947888,
      "name": "sd_zbc_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:73",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585947888,
      "name": "sd_zbc_report_zones.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586195056,
      "name": "sd_zbc_report_zones",
      "external": false,
      "loc": "drivers/scsi/sd_zbc.c:73",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones",
        "drivers/scsi/sd_zbc.c:sd_zbc_read_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195056,
      "name": "sd_zbc_report_zones.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 398
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586337840,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:130",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586337840,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586581104,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586581104,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586728464,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586728464,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587532784,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:192",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532784,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587598976,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:193",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587598976,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587479392,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:193",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587479392,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:192",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592530220,
      "name": "sd_zbc_report_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    },
    {
      "addr": 18446744071588055040,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 664
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:251",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594401971,
      "name": "sd_zbc_report_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071589420112,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:254",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596261928,
      "name": "sd_zbc_report_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071590996368,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:256",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596790132,
      "name": "sd_zbc_report_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071591350064,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void * data)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:256",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597699257,
      "name": "sd_zbc_report_zones.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071591699968,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499639808,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499639808,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232094428,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232094428,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292961360,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292961360,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276822514,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276822514,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1124
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586418944,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586418944,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586295200,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295200,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586683024,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586683024,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones)
```

```json
{
  "name": "sd_zbc_report_zones",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586789056,
      "name": "sd_zbc_report_zones",
      "external": true,
      "loc": "drivers/scsi/sd_zbc.c:163",
      "file": "drivers/scsi/sd_zbc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586789056,
      "name": "sd_zbc_report_zones",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
int sd_zbc_report_zones(struct gendisk * disk, sector_t sector, struct blk_zone * zones, unsigned int * nr_zones, gfp_t gfp_mask)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>report_zones_cb cb</code>
</li>
<li>
<b>Param added. </b>
<code>void * data</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_zone * zones</code>
</li>
<li>
<b>Param reordered. </b>
<code>disk, sector, zones, nr_zones</code> ➡️ <code>disk, sector, nr_zones, cb, data</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int * nr_zones</code> ➡️ <code>unsigned int nr_zones</code>
</li>
</ul>
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

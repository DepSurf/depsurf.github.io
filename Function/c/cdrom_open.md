# Function: <code>cdrom_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585138432,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1150",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585138432,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2629
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585531200,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1150",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585531200,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585719088,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1150",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719088,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805760,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1148",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805760,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2471
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586244816,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1148",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586244816,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2531
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1148",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586512198,
      "name": "cdrom_open.cold.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071586503216,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1148",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586660714,
      "name": "cdrom_open.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071586651232,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1149",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586914455,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071586906144,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 992
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1155",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587111892,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071587103552,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587957456,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1158",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587957456,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588018080,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1158",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588018080,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587899488,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1158",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587899488,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1158",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592555872,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071588508416,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1158",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594435255,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071589914688,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1158",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596271018,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071591492896,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int cdrom_open(struct cdrom_device_info * cdi, blk_mode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1150",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596800399,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071591908864,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int cdrom_open(struct cdrom_device_info * cdi, blk_mode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1150",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597724005,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071592648704,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500169816,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1155",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500169816,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1092
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232647636,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1155",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232647636,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1024
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293454144,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1155",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293454144,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1428
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
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277103648,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1155",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277103648,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 998
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1155",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817972,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071586809632,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1155",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759812,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071586751472,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1155",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066452,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071587058112,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int cdrom_open(struct cdrom_device_info * cdi, struct block_device * bdev, fmode_t mode)
```

```json
{
  "name": "cdrom_open",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cdrom_open",
      "external": true,
      "loc": "drivers/cdrom/cdrom.c:1155",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sr.c:sr_block_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587173620,
      "name": "cdrom_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071587165280,
      "name": "cdrom_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1007
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct block_device * bdev</code>
</li>
<li>
<b>Param reordered. </b>
<code>cdi, bdev, mode</code> ➡️ <code>cdi, mode</code>
</li>
<li>
<b>Param type changed. </b>
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
</li>
</ul>
</details>
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

# Function: <code>scsi_partsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780736,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:125",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780736,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585140896,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:125",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585140896,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585335184,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:125",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585335184,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585421124,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:125",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585420800,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071585421056,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585851156,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585850832,
      "name": "scsi_partsize.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    },
    {
      "addr": 18446744071585851088,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586097925,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586097600,
      "name": "scsi_partsize.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071586097840,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586244021,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586243696,
      "name": "scsi_partsize.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    },
    {
      "addr": 18446744071586243936,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586487669,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586487344,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071586487584,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586635461,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586635136,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071586635376,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool scsi_partsize(struct block_device * bdev, sector_t capacity, int * geom)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587431264,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:61",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587431264,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
bool scsi_partsize(struct block_device * bdev, sector_t capacity, int * geom)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587499984,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:61",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587499984,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
bool scsi_partsize(struct block_device * bdev, sector_t capacity, int * geom)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587381696,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:62",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381696,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
bool scsi_partsize(struct block_device * bdev, sector_t capacity, int * geom)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587953152,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:62",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587953152,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
bool scsi_partsize(struct block_device * bdev, sector_t capacity, int * geom)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589308768,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:60",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589308768,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
bool scsi_partsize(struct block_device * bdev, sector_t capacity, int * geom)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590873456,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:60",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590873456,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
bool scsi_partsize(struct block_device * bdev, sector_t capacity, int * geom)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591216640,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:60",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591216640,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
bool scsi_partsize(struct block_device * bdev, sector_t capacity, int * geom)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591563824,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:60",
      "file": "drivers/scsi/scsicam.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591563824,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499531212,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499530488,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446603336499530760,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231996404,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231995984,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 3231996268,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292821948,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292821520,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 13835058055292821808,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276735054,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276734628,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446743936276734916,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586325941,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586325616,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071586325856,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586167269,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166944,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071586167184,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586583429,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586583104,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071586583344,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int scsi_partsize(unsigned char * buf, long unsigned int capacity, unsigned int * cyls, unsigned int * hds, unsigned int * secs)
```

```json
{
  "name": "scsi_partsize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586695653,
      "name": "scsi_partsize",
      "external": true,
      "loc": "drivers/scsi/scsicam.c:126",
      "file": "drivers/scsi/scsicam.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ],
      "caller_func": [
        "drivers/scsi/scsicam.c:scsicam_bios_param"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695328,
      "name": "scsi_partsize.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071586695568,
      "name": "scsi_partsize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device * bdev</code>
</li>
<li>
<b>Param added. </b>
<code>int * geom</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int * cyls</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int * hds</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int * secs</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int capacity</code> ➡️ <code>sector_t capacity</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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

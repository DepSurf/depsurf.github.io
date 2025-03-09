# Function: <code>sbitmap_resize</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583572045,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:65",
      "file": "lib/sbitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_resize"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571856,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583609520,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:67",
      "file": "lib/sbitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_resize"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583609296,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583855568,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:67",
      "file": "lib/sbitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_resize"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855344,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584057788,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:67",
      "file": "lib/sbitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_queue_resize"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055648,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140416,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:102",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140416,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584330640,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330640,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465264,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465264,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585027536,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585027536,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585178384,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:79",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585178384,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585060880,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:128",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize",
        "drivers/scsi/scsi.c:scsi_track_queue_full"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585060880,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:128",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize",
        "drivers/scsi/scsi.c:scsi_track_queue_full"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592341401,
      "name": "sbitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071585507152,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:123",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize",
        "drivers/scsi/scsi.c:scsi_track_queue_full",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594201860,
      "name": "sbitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071586655248,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:123",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize",
        "drivers/scsi/scsi.c:scsi_track_queue_full",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596201736,
      "name": "sbitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071587901568,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:123",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize",
        "drivers/scsi/scsi.c:scsi_track_queue_full",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596726940,
      "name": "sbitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588173152,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:123",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize",
        "drivers/scsi/scsi.c:scsi_track_queue_full",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map",
        "drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597635289,
      "name": "sbitmap_resize.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588463968,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496356672,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496356672,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229688504,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229688504,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290678976,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290678976,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275399898,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275399898,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434016,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434016,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584369120,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369120,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584416928,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416928,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```

```json
{
  "name": "sbitmap_resize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584522976,
      "name": "sbitmap_resize",
      "external": true,
      "loc": "lib/sbitmap.c:89",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_swqueue",
        "lib/sbitmap.c:sbitmap_queue_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522976,
      "name": "sbitmap_resize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void sbitmap_resize(struct sbitmap * sb, unsigned int depth)
```
</details>
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

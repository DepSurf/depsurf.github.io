# Function: <code>blk_queue_segment_boundary</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582770592,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:761",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582770592,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583048992,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:761",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048992,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154592,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:785",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154592,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211760,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:797",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211760,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388464,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:798",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388464,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:798",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583600143,
      "name": "blk_queue_segment_boundary.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583598288,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:740",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706383,
      "name": "blk_queue_segment_boundary.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583704560,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:728",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894943,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583893136,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:729",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998303,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583996432,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:690",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387329,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584385120,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:703",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372595,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584499264,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:700",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315194,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584533776,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:700",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592313245,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584944736,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:732",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594095971,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071585647696,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420256,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:733",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420256,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586667760,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:739",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667760,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586938816,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:742",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938816,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495823976,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:729",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495823976,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229173256,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:729",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229173256,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290012832,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:729",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290012832,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274958670,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:729",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274958670,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:729",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583967039,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583965168,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:729",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903951,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583902080,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:729",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950799,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071583948928,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_queue_segment_boundary(struct request_queue * q, long unsigned int mask)
```

```json
{
  "name": "blk_queue_segment_boundary",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_queue_segment_boundary",
      "external": true,
      "loc": "block/blk-settings.c:729",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584052783,
      "name": "blk_queue_segment_boundary.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071584050912,
      "name": "blk_queue_segment_boundary",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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

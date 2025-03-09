# Function: <code>blk_queue_free_zone_bitmaps</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583875713,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:393",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583875616,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584065220,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:397",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584066240,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584187912,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:436",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188992,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584583392,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:379",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583392,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700816,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:414",
      "file": "block/blk-zoned.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700816,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584729443,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:406",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_queue_clear_zone_settings"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584728880,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585157139,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:460",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_queue_clear_zone_settings"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585156576,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585892354,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:453",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_queue_clear_zone_settings"
      ],
      "caller_func": [
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891760,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496054156,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:436",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496055472,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229383424,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:436",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229384628,
      "name": "blk_queue_free_zone_bitmaps",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290287708,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:436",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290289296,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275130114,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:436",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275131254,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584156648,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:436",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157728,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584091912,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:436",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584092992,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584140408,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:436",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141488,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```

```json
{
  "name": "blk_queue_free_zone_bitmaps",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584244568,
      "name": "blk_queue_free_zone_bitmaps",
      "external": true,
      "loc": "block/blk-zoned.c:436",
      "file": "block/blk-zoned.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blk_revalidate_disk_zones"
      ],
      "caller_func": [
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245648,
      "name": "blk_queue_free_zone_bitmaps",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void blk_queue_free_zone_bitmaps(struct request_queue * q)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue * q)
```
</details>
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

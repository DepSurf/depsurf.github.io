# Function: <code>lookup_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct block_device * lookup_bdev(const char * pathname, int mask)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581238224,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:1771",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:SyS_quotactl",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238224,
      "name": "lookup_bdev.part.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071581238432,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct block_device * lookup_bdev(const char * pathname, int mask)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581408894,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:1850",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:SyS_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404208,
      "name": "lookup_bdev.part.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071581404432,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct block_device * lookup_bdev(const char * pathname, int mask)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581488622,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2172",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:SyS_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581484448,
      "name": "lookup_bdev.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071581484672,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct block_device * lookup_bdev(const char * pathname, int mask)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544974,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2088",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:SyS_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581544672,
      "name": "lookup_bdev.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071581544896,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct block_device * lookup_bdev(const char * pathname, int mask)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581687822,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2084",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:SyS_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687520,
      "name": "lookup_bdev.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071581687744,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct block_device * lookup_bdev(const char * pathname, int mask)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581850750,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2100",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581850432,
      "name": "lookup_bdev.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071581850656,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct block_device * lookup_bdev(const char * pathname, int mask)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581938286,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2134",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581937968,
      "name": "lookup_bdev.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071581938192,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct block_device * lookup_bdev(const char * pathname, int mask)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582076110,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2175",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582075792,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071582076016,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582153557,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2157",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151296,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071582151472,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582388752,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2176",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388752,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int lookup_bdev(const char * pathname, dev_t * dev)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582436112,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:1856",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:quotactl_block",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582436112,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int lookup_bdev(const char * pathname, dev_t * dev)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582462896,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:1865",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:quotactl_block",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582462896,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int lookup_bdev(const char * pathname, dev_t * dev)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584889984,
      "name": "lookup_bdev",
      "external": true,
      "loc": "block/bdev.c:969",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quotactl_block",
        "block/bdev.c:blkdev_get_by_path",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584889984,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int lookup_bdev(const char * pathname, dev_t * dev)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585588720,
      "name": "lookup_bdev",
      "external": true,
      "loc": "block/bdev.c:973",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quotactl_block",
        "block/bdev.c:blkdev_get_by_path",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585588720,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int lookup_bdev(const char * pathname, dev_t * dev)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586355248,
      "name": "lookup_bdev",
      "external": true,
      "loc": "block/bdev.c:972",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/quota.c:quotactl_block",
        "block/bdev.c:blkdev_get_by_path",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586355248,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int lookup_bdev(const char * pathname, dev_t * dev)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586601888,
      "name": "lookup_bdev",
      "external": true,
      "loc": "block/bdev.c:934",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "fs/quota/quota.c:quotactl_block",
        "block/bdev.c:blkdev_get_by_path",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586601888,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int lookup_bdev(const char * pathname, dev_t * dev)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586871200,
      "name": "lookup_bdev",
      "external": true,
      "loc": "block/bdev.c:1005",
      "file": "block/bdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:resume_store",
        "fs/super.c:mount_bdev",
        "fs/super.c:get_tree_bdev",
        "fs/quota/quota.c:quotactl_block",
        "block/bdev.c:bdev_open_by_path",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586871200,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493705860,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2157",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493703504,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446603336493703704,
      "name": "lookup_bdev",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227233464,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2157",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/mtd/mtdsuper.c:get_tree_mtd",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227231000,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 3227231184,
      "name": "lookup_bdev",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287310440,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2157",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287307456,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 13835058055287307680,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273321806,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2157",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273319862,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446743936273319990,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582122293,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2157",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120032,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071582120208,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582059733,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2157",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057472,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071582057648,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582112773,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2157",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110512,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071582110688,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct block_device * lookup_bdev(const char * pathname)
```

```json
{
  "name": "lookup_bdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582185733,
      "name": "lookup_bdev",
      "external": true,
      "loc": "fs/block_dev.c:2157",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get_by_path"
      ],
      "caller_func": [
        "fs/block_dev.c:blkdev_get_by_path",
        "fs/quota/quota.c:kernel_quotactl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582183472,
      "name": "lookup_bdev.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071582183648,
      "name": "lookup_bdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int mask</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>dev_t * dev</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct block_device *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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

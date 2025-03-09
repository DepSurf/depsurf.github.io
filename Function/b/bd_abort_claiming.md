# Function: <code>bd_abort_claiming</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582071072,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582071072,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582148656,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582148656,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582389683,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1218",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582385440,
      "name": "bd_abort_claiming",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582440064,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1084",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:truncate_bdev_range",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440064,
      "name": "bd_abort_claiming",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void bd_abort_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582467168,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1090",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:truncate_bdev_range",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467168,
      "name": "bd_abort_claiming",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bd_abort_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584892251,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "block/bdev.c:646",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:truncate_bdev_range"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584891376,
      "name": "bd_abort_claiming",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bd_abort_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585591090,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "block/bdev.c:651",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:truncate_bdev_range"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585589360,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bd_abort_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586357794,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "block/bdev.c:650",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:truncate_bdev_range"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586355664,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bd_abort_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586604401,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "block/bdev.c:600",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:truncate_bdev_range"
      ],
      "caller_func": [
        "block/genhd.c:disk_scan_partitions",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602640,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bd_abort_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586875860,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "block/bdev.c:591",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_open_by_dev",
        "block/bdev.c:truncate_bdev_range"
      ],
      "caller_func": [
        "block/genhd.c:disk_scan_partitions",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586871952,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493699720,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493699720,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227227016,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227227016,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287296688,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287296688,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273316560,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273316560,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582117392,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582117392,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054832,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054832,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582107872,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107872,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```

```json
{
  "name": "bd_abort_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582180240,
      "name": "bd_abort_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1237",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582180240,
      "name": "bd_abort_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void bd_abort_claiming(struct block_device * bdev, struct block_device * whole, void * holder)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct block_device * whole</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdev, whole, holder</code> ➡️ <code>bdev, holder</code>
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

# Function: <code>bdev_disk_changed</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582151760,
      "name": "bdev_disk_changed",
      "external": false,
      "loc": "fs/block_dev.c:1511",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151760,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582384544,
      "name": "bdev_disk_changed",
      "external": true,
      "loc": "fs/block_dev.c:1492",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkdev_common_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384544,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435344,
      "name": "bdev_disk_changed",
      "external": true,
      "loc": "fs/block_dev.c:1236",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435344,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582466112,
      "name": "bdev_disk_changed",
      "external": true,
      "loc": "fs/block_dev.c:1242",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/loop.c:loop_change_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582466112,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bdev_disk_changed(struct gendisk * disk, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585033344,
      "name": "bdev_disk_changed",
      "external": true,
      "loc": "block/partitions/core.c:665",
      "file": "block/partitions/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_get_whole",
        "block/bdev.c:blkdev_get_whole",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_reread_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032784,
      "name": "bdev_disk_changed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
    },
    {
      "addr": 18446744071592315939,
      "name": "bdev_disk_changed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071585033344,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bdev_disk_changed(struct gendisk * disk, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585750512,
      "name": "bdev_disk_changed",
      "external": true,
      "loc": "block/partitions/core.c:653",
      "file": "block/partitions/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_get_whole",
        "block/bdev.c:blkdev_get_whole",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_reread_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585749984,
      "name": "bdev_disk_changed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
    },
    {
      "addr": 18446744071594100487,
      "name": "bdev_disk_changed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 18446744071585750512,
      "name": "bdev_disk_changed",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int bdev_disk_changed(struct gendisk * disk, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586533776,
      "name": "bdev_disk_changed",
      "external": true,
      "loc": "block/partitions/core.c:655",
      "file": "block/partitions/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_get_whole",
        "block/bdev.c:blkdev_get_whole",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_reread_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532928,
      "name": "bdev_disk_changed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
    },
    {
      "addr": 18446744071596108562,
      "name": "bdev_disk_changed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586533776,
      "name": "bdev_disk_changed",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int bdev_disk_changed(struct gendisk * disk, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bdev_disk_changed",
      "external": true,
      "loc": "block/partitions/core.c:652",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_get_whole",
        "block/bdev.c:blkdev_get_whole",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_reread_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596632365,
      "name": "bdev_disk_changed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586778448,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1079
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
int bdev_disk_changed(struct gendisk * disk, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587055808,
      "name": "bdev_disk_changed",
      "external": true,
      "loc": "block/partitions/core.c:646",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bdev.c:blkdev_get_whole",
        "block/bdev.c:blkdev_get_whole",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_reread_partitions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055808,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 477
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
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493704152,
      "name": "bdev_disk_changed",
      "external": false,
      "loc": "fs/block_dev.c:1511",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493704152,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227231660,
      "name": "bdev_disk_changed",
      "external": false,
      "loc": "fs/block_dev.c:1511",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227231660,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287308256,
      "name": "bdev_disk_changed",
      "external": false,
      "loc": "fs/block_dev.c:1511",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287308256,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273320346,
      "name": "bdev_disk_changed",
      "external": false,
      "loc": "fs/block_dev.c:1511",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273320346,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120496,
      "name": "bdev_disk_changed",
      "external": false,
      "loc": "fs/block_dev.c:1511",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120496,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057936,
      "name": "bdev_disk_changed",
      "external": false,
      "loc": "fs/block_dev.c:1511",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057936,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110976,
      "name": "bdev_disk_changed",
      "external": false,
      "loc": "fs/block_dev.c:1511",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110976,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```

```json
{
  "name": "bdev_disk_changed",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582183936,
      "name": "bdev_disk_changed",
      "external": false,
      "loc": "fs/block_dev.c:1511",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582183936,
      "name": "bdev_disk_changed",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void bdev_disk_changed(struct block_device * bdev, bool invalidate)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk * disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device * bdev</code>
</li>
</ul>
</details>
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

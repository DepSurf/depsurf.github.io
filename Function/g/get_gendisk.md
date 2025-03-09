# Function: <code>get_gendisk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582821136,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:683",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582821136,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583100384,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:709",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583100384,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583211904,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:709",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211904,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583269952,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:721",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269952,
      "name": "get_gendisk",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447968,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:782",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447968,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583659840,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:818",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659840,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583766112,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:840",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766112,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583955456,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:862",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955456,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584058928,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:871",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584058928,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584460176,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:976",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584460176,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495899448,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:871",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495899448,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229242260,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:871",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229242260,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290106752,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:871",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290106752,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275016092,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:871",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275016092,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027664,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:871",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027664,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963472,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:871",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963472,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584011424,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:871",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584011424,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
struct gendisk * get_gendisk(dev_t devt, int * partno)
```

```json
{
  "name": "get_gendisk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584114352,
      "name": "get_gendisk",
      "external": true,
      "loc": "block/genhd.c:871",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:software_resume",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkcg_conf_get_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114352,
      "name": "get_gendisk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct gendisk * get_gendisk(dev_t devt, int * partno)
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

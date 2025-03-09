# Function: <code>dm_prepare_ioctl</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587262000,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:461",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587262000,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587442272,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:512",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442272,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587720608,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587720608,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587924336,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587924336,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588772608,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:523",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772608,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588792208,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:520",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792208,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588677152,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:525",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588677152,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589364416,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:406",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364416,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590839904,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:415",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590839904,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592531664,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:410",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592531664,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592961520,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:412",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592961520,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593711648,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:412",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593711648,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501152488,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501152488,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233671972,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233671972,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294670736,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294670736,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277868204,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277868204,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587555312,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587555312,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587323408,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323408,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587880480,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587880480,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```

```json
{
  "name": "dm_prepare_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587997456,
      "name": "dm_prepare_ioctl",
      "external": false,
      "loc": "drivers/md/dm.c:492",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:dm_blk_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997456,
      "name": "dm_prepare_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int dm_prepare_ioctl(struct mapped_device * md, int * srcu_idx, struct block_device * * bdev)
```
</details>
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

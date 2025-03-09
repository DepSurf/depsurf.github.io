# Function: <code>bd_start_claiming</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581241433,
      "name": "bd_start_claiming",
      "external": false,
      "loc": "fs/block_dev.c:839",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581408121,
      "name": "bd_start_claiming",
      "external": false,
      "loc": "fs/block_dev.c:917",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581487577,
      "name": "bd_start_claiming",
      "external": false,
      "loc": "fs/block_dev.c:1169",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581542497,
      "name": "bd_start_claiming",
      "external": false,
      "loc": "fs/block_dev.c:1094",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581685361,
      "name": "bd_start_claiming",
      "external": false,
      "loc": "fs/block_dev.c:1084",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581848787,
      "name": "bd_start_claiming",
      "external": false,
      "loc": "fs/block_dev.c:1106",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581936307,
      "name": "bd_start_claiming",
      "external": false,
      "loc": "fs/block_dev.c:1145",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582074064,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582074064,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582150208,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582150208,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582388944,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1123",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582388944,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493700552,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493700552,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227228784,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227228784,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287305504,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287305504,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273318458,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273318458,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118944,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118944,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056384,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056384,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109424,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109424,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
```

```json
{
  "name": "bd_start_claiming",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182368,
      "name": "bd_start_claiming",
      "external": true,
      "loc": "fs/block_dev.c:1142",
      "file": "fs/block_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "drivers/block/loop.c:loop_set_fd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182368,
      "name": "bd_start_claiming",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
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
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct block_device * bd_start_claiming(struct block_device * bdev, void * holder)
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

# Function: <code>bdev_del_partition</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bdev_del_partition(struct block_device * bdev, int partno)
```

```json
{
  "name": "bdev_del_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471376,
      "name": "bdev_del_partition",
      "external": true,
      "loc": "block/partitions/core.c:524",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkpg_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471376,
      "name": "bdev_del_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int bdev_del_partition(struct block_device * bdev, int partno)
```

```json
{
  "name": "bdev_del_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584585760,
      "name": "bdev_del_partition",
      "external": true,
      "loc": "block/partitions/core.c:468",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkpg_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585760,
      "name": "bdev_del_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int bdev_del_partition(struct block_device * bdev, int partno)
```

```json
{
  "name": "bdev_del_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584617712,
      "name": "bdev_del_partition",
      "external": true,
      "loc": "block/partitions/core.c:465",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkpg_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584617712,
      "name": "bdev_del_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int bdev_del_partition(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdev_del_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585032336,
      "name": "bdev_del_partition",
      "external": true,
      "loc": "block/partitions/core.c:479",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkpg_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032336,
      "name": "bdev_del_partition",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int bdev_del_partition(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdev_del_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585749504,
      "name": "bdev_del_partition",
      "external": true,
      "loc": "block/partitions/core.c:470",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkpg_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585749504,
      "name": "bdev_del_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int bdev_del_partition(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdev_del_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586532384,
      "name": "bdev_del_partition",
      "external": true,
      "loc": "block/partitions/core.c:469",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkpg_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532384,
      "name": "bdev_del_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int bdev_del_partition(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdev_del_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586779904,
      "name": "bdev_del_partition",
      "external": true,
      "loc": "block/partitions/core.c:477",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkpg_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586779904,
      "name": "bdev_del_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int bdev_del_partition(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdev_del_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587056672,
      "name": "bdev_del_partition",
      "external": true,
      "loc": "block/partitions/core.c:460",
      "file": "block/partitions/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioctl.c:blkpg_do_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587056672,
      "name": "bdev_del_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bdev_del_partition(struct block_device * bdev, int partno)
```
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

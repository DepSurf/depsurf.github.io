# Function: <code>compat_blkdev_driver_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582933142,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:524",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583220544,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:524",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583326528,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:524",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583385484,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:208",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583564831,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:209",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583780732,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:209",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583860796,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:209",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
int compat_blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584051136,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:209",
      "file": "block/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584051136,
      "name": "compat_blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 901
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584174253,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:210",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
int compat_blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496035904,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:210",
      "file": "block/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496035904,
      "name": "compat_blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2036
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int compat_blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290266176,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:210",
      "file": "block/compat_ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290266176,
      "name": "compat_blkdev_driver_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1548
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584142989,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:210",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584078525,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:210",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584126749,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:210",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compat_blkdev_driver_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584230797,
      "name": "compat_blkdev_driver_ioctl",
      "external": false,
      "loc": "block/compat_ioctl.c:210",
      "file": "block/compat_ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/compat_ioctl.c:compat_blkdev_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int compat_blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int compat_blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int compat_blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int compat_blkdev_driver_ioctl(struct block_device * bdev, fmode_t mode, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
</ul>

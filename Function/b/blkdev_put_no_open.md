# Function: <code>blkdev_put_no_open</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blkdev_put_no_open(struct block_device * bdev)
```

```json
{
  "name": "blkdev_put_no_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582441379,
      "name": "blkdev_put_no_open",
      "external": true,
      "loc": "fs/block_dev.c:1394",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_put"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582444672,
      "name": "blkdev_put_no_open",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blkdev_put_no_open(struct block_device * bdev)
```

```json
{
  "name": "blkdev_put_no_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582468451,
      "name": "blkdev_put_no_open",
      "external": true,
      "loc": "fs/block_dev.c:1397",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_put"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471664,
      "name": "blkdev_put_no_open",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blkdev_put_no_open(struct block_device * bdev)
```

```json
{
  "name": "blkdev_put_no_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584892531,
      "name": "blkdev_put_no_open",
      "external": true,
      "loc": "block/bdev.c:762",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584895088,
      "name": "blkdev_put_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void blkdev_put_no_open(struct block_device * bdev)
```

```json
{
  "name": "blkdev_put_no_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585590677,
      "name": "blkdev_put_no_open",
      "external": true,
      "loc": "block/bdev.c:761",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585594112,
      "name": "blkdev_put_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void blkdev_put_no_open(struct block_device * bdev)
```

```json
{
  "name": "blkdev_put_no_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586361622,
      "name": "blkdev_put_no_open",
      "external": true,
      "loc": "block/bdev.c:760",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_statx_dioalign",
        "block/bdev.c:blkdev_put"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_open_bdev",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586361104,
      "name": "blkdev_put_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void blkdev_put_no_open(struct block_device * bdev)
```

```json
{
  "name": "blkdev_put_no_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586608003,
      "name": "blkdev_put_no_open",
      "external": true,
      "loc": "block/bdev.c:743",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_statx_dioalign",
        "block/bdev.c:blkdev_put"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_exit",
        "block/blk-cgroup.c:blkg_conf_open_bdev",
        "block/blk-cgroup.c:blkg_conf_open_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586607488,
      "name": "blkdev_put_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void blkdev_put_no_open(struct block_device * bdev)
```

```json
{
  "name": "blkdev_put_no_open",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586877523,
      "name": "blkdev_put_no_open",
      "external": true,
      "loc": "block/bdev.c:734",
      "file": "block/bdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_statx_dioalign",
        "block/bdev.c:bdev_release",
        "block/bdev.c:bdev_open_by_dev"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_exit",
        "block/blk-cgroup.c:blkg_conf_open_bdev",
        "block/blk-cgroup.c:blkg_conf_open_bdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877008,
      "name": "blkdev_put_no_open",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void blkdev_put_no_open(struct block_device * bdev)
```
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

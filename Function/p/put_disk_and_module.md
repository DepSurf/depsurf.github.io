# Function: <code>put_disk_and_module</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583660117,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1494",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583660416,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583766389,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1519",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766688,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583955729,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1540",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956096,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584059201,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1549",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584059568,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584460464,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1762",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455600,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495899848,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1549",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495899384,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229242508,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1549",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229243036,
      "name": "put_disk_and_module",
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
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290107144,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1549",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290107728,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275016366,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1549",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275016766,
      "name": "put_disk_and_module",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584027937,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1549",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028304,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583963745,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1549",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964112,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584011697,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1549",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012064,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "put_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584114625,
      "name": "put_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1549",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_start_claiming",
        "block/blk-cgroup.c:blkg_conf_finish",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkcg_conf_get_disk",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_cost_model_write",
        "block/blk-iocost.c:ioc_qos_write",
        "block/blk-iocost.c:ioc_qos_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114992,
      "name": "put_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void put_disk_and_module(struct gendisk * disk)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void put_disk_and_module(struct gendisk * disk)
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

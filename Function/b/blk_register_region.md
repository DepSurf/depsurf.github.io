# Function: <code>blk_register_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582817440,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:476",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:add_disk"
      ],
      "caller_func": [
        "drivers/block/brd.c:brd_init",
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817440,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583101932,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:477",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:device_add_disk"
      ],
      "caller_func": [
        "drivers/block/brd.c:brd_init",
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096592,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583213449,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:477",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208096,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583271504,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:478",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:device_add_disk"
      ],
      "caller_func": [
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266256,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583451829,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:523",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445936,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583663407,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:538",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583657168,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583770218,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:551",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583763440,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583959426,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952928,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584063254,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056400,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584459849,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:650",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584452608,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495905212,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495896376,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229247972,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229239492,
      "name": "blk_register_region",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290113284,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290101824,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275020452,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275013242,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584031990,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025136,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583967782,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960944,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584015750,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008896,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
```

```json
{
  "name": "blk_register_region",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584118304,
      "name": "blk_register_region",
      "external": true,
      "loc": "block/genhd.c:564",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:__device_add_disk"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sd.c:sd_remove",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111392,
      "name": "blk_register_region",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_register_region(dev_t devt, long unsigned int range, struct module * module, struct kobject * (*)(dev_t, int *, void *) probe, int (*)(dev_t, void *) lock, void * data)
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

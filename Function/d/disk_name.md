# Function: <code>disk_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582830880,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:34",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:flush_disk",
        "fs/block_dev.c:check_disk_size_change",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830880,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583110496,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583110496,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583222016,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583222016,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276048,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:34",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276048,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583456304,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583456304,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583667712,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667712,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583774816,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583774816,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583964656,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964656,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584068016,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068016,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584456755,
      "name": "disk_name",
      "external": true,
      "loc": "block/genhd.c:77",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:bdevname"
      ],
      "caller_func": [
        "block/bio.c:bio_devname",
        "block/blk-settings.c:disk_stack_limits",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/genhd.c:bdevname",
        "block/partitions/core.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584454288,
      "name": "disk_name.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071584458624,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584573427,
      "name": "disk_name",
      "external": true,
      "loc": "block/genhd.c:94",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:bdevname"
      ],
      "caller_func": [
        "block/bio.c:bio_devname",
        "block/blk-settings.c:disk_stack_limits",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/genhd.c:bdevname",
        "block/partitions/core.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571184,
      "name": "disk_name.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071591372911,
      "name": "disk_name.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584574352,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584605546,
      "name": "disk_name",
      "external": true,
      "loc": "block/genhd.c:91",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:bdevname"
      ],
      "caller_func": [
        "block/blk-settings.c:disk_stack_limits",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/genhd.c:bdevname",
        "block/partitions/core.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584603568,
      "name": "disk_name.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071591315509,
      "name": "disk_name.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584607040,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495911240,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495911240,
      "name": "disk_name",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229253804,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229253804,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290120416,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290120416,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275025344,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275025344,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584036752,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036752,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583972512,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972512,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584020512,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020512,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
char * disk_name(struct gendisk * hd, int partno, char * buf)
```

```json
{
  "name": "disk_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584123056,
      "name": "disk_name",
      "external": true,
      "loc": "block/partition-generic.c:35",
      "file": "block/partition-generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:printk_all_partitions",
        "block/partition-generic.c:bio_devname",
        "block/partition-generic.c:bdevname",
        "block/partitions/check.c:check_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123056,
      "name": "disk_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
char * disk_name(struct gendisk * hd, int partno, char * buf)
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

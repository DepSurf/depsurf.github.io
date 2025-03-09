# Function: <code>bdi_alloc</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581285180,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:36",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581424572,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:37",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581581622,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:38",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581667958,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:38",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581785366,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:38",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581857590,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info * bdi_alloc(int node_id)
```

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581433120,
      "name": "bdi_alloc",
      "external": true,
      "loc": "mm/backing-dev.c:867",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "block/blk-core.c:__blk_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433120,
      "name": "bdi_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
struct backing_dev_info * bdi_alloc(int node_id)
```

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475632,
      "name": "bdi_alloc",
      "external": true,
      "loc": "mm/backing-dev.c:734",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "block/blk-core.c:blk_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475632,
      "name": "bdi_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct backing_dev_info * bdi_alloc(int node_id)
```

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581496384,
      "name": "bdi_alloc",
      "external": true,
      "loc": "mm/backing-dev.c:733",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "block/blk-core.c:blk_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496384,
      "name": "bdi_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct backing_dev_info * bdi_alloc(int node_id)
```

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581756864,
      "name": "bdi_alloc",
      "external": true,
      "loc": "mm/backing-dev.c:806",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756864,
      "name": "bdi_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
struct backing_dev_info * bdi_alloc(int node_id)
```

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139056,
      "name": "bdi_alloc",
      "external": true,
      "loc": "mm/backing-dev.c:796",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139056,
      "name": "bdi_alloc",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info * bdi_alloc(int node_id)
```

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616512,
      "name": "bdi_alloc",
      "external": true,
      "loc": "mm/backing-dev.c:919",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616512,
      "name": "bdi_alloc",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info * bdi_alloc(int node_id)
```

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582825248,
      "name": "bdi_alloc",
      "external": true,
      "loc": "mm/backing-dev.c:932",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582825248,
      "name": "bdi_alloc",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct backing_dev_info * bdi_alloc(int node_id)
```

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582999664,
      "name": "bdi_alloc",
      "external": true,
      "loc": "mm/backing-dev.c:928",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582999664,
      "name": "bdi_alloc",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493326692,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "bdi_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226923192,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
      ],
      "caller_func": []
    },
    {
      "addr": 3243885168,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "drivers/mtd/mtdcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/mtdcore.c:init_mtd"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286867608,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273058904,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581826326,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581763990,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581817638,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
  "name": "bdi_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581887286,
      "name": "bdi_alloc",
      "external": false,
      "loc": "include/linux/backing-dev.h:40",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:super_setup_bdi_name"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct backing_dev_info * bdi_alloc(int node_id)
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

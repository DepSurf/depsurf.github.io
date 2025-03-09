# Function: <code>get_disk_and_module</code>

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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583659216,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1463",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659216,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583765488,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1488",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583765488,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954352,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1509",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954352,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057824,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1518",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057824,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584457829,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1731",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:exact_lock"
      ],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584453728,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495898232,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1518",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495898232,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229241568,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1518",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229241568,
      "name": "get_disk_and_module",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290105232,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1518",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290105232,
      "name": "get_disk_and_module",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275015130,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1518",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275015130,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584026560,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1518",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026560,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583962368,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1518",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962368,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584010320,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1518",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584010320,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct kobject * get_disk_and_module(struct gendisk * disk)
```

```json
{
  "name": "get_disk_and_module",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584112832,
      "name": "get_disk_and_module",
      "external": true,
      "loc": "block/genhd.c:1518",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:get_gendisk",
        "block/genhd.c:exact_lock",
        "drivers/block/loop.c:loop_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112832,
      "name": "get_disk_and_module",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct kobject * get_disk_and_module(struct gendisk * disk)
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
struct kobject * get_disk_and_module(struct gendisk * disk)
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

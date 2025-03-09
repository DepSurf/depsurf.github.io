# Function: <code>propagate_active_weight</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584156032,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584156032,
      "name": "propagate_active_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584556033,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:949",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:weight_updated"
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
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496007312,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496007312,
      "name": "propagate_active_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229349292,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229349292,
      "name": "propagate_active_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290239232,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290239232,
      "name": "propagate_active_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275106136,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:weight_updated"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124768,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124768,
      "name": "propagate_active_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584060432,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584060432,
      "name": "propagate_active_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584108528,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584108528,
      "name": "propagate_active_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```

```json
{
  "name": "propagate_active_weight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212560,
      "name": "propagate_active_weight",
      "external": false,
      "loc": "block/blk-iocost.c:951",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212560,
      "name": "propagate_active_weight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void propagate_active_weight(struct ioc_gq * iocg, u32 active, u32 inuse)
```
</details>
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

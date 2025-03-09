# Function: <code>ioc_lat_stat</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584163935,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1271",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
void ioc_lat_stat(struct ioc * ioc, u32 * missed_ppm_ar, u32 * rq_wait_pct_p)
```

```json
{
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584551664,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1270",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584551664,
      "name": "ioc_lat_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void ioc_lat_stat(struct ioc * ioc, u32 * missed_ppm_ar, u32 * rq_wait_pct_p)
```

```json
{
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584662560,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1554",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662560,
      "name": "ioc_lat_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584708877,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1561",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585132581,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1561",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585861519,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1560",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void ioc_lat_stat(struct ioc * ioc, u32 * missed_ppm_ar, u32 * rq_wait_pct_p)
```

```json
{
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586630368,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1565",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630368,
      "name": "ioc_lat_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
void ioc_lat_stat(struct ioc * ioc, u32 * missed_ppm_ar, u32 * rq_wait_pct_p)
```

```json
{
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586891136,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1581",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586891136,
      "name": "ioc_lat_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
void ioc_lat_stat(struct ioc * ioc, u32 * missed_ppm_ar, u32 * rq_wait_pct_p)
```

```json
{
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587169104,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1588",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587169104,
      "name": "ioc_lat_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496016324,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1271",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229358328,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1271",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290249820,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1271",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275108786,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1271",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584132671,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1271",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584068255,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1271",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584116431,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1271",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
  "name": "ioc_lat_stat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584220031,
      "name": "ioc_lat_stat",
      "external": false,
      "loc": "block/blk-iocost.c:1271",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_timer_fn"
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
void ioc_lat_stat(struct ioc * ioc, u32 * missed_ppm_ar, u32 * rq_wait_pct_p)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void ioc_lat_stat(struct ioc * ioc, u32 * missed_ppm_ar, u32 * rq_wait_pct_p)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void ioc_lat_stat(struct ioc * ioc, u32 * missed_ppm_ar, u32 * rq_wait_pct_p)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>

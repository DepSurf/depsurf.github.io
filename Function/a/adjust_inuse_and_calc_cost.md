# Function: <code>adjust_inuse_and_calc_cost</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq * iocg, u64 vtime, u64 abs_cost, struct ioc_now * now)
```

```json
{
  "name": "adjust_inuse_and_calc_cost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584678528,
      "name": "adjust_inuse_and_calc_cost",
      "external": false,
      "loc": "block/blk-iocost.c:2409",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584678528,
      "name": "adjust_inuse_and_calc_cost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
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
u64 adjust_inuse_and_calc_cost(struct ioc_gq * iocg, u64 vtime, u64 abs_cost, struct ioc_now * now)
```

```json
{
  "name": "adjust_inuse_and_calc_cost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584706608,
      "name": "adjust_inuse_and_calc_cost",
      "external": false,
      "loc": "block/blk-iocost.c:2416",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584706608,
      "name": "adjust_inuse_and_calc_cost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq * iocg, u64 vtime, u64 abs_cost, struct ioc_now * now)
```

```json
{
  "name": "adjust_inuse_and_calc_cost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_inuse_and_calc_cost",
      "external": false,
      "loc": "block/blk-iocost.c:2423",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585130048,
      "name": "adjust_inuse_and_calc_cost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 625
    },
    {
      "addr": 18446744071592320717,
      "name": "adjust_inuse_and_calc_cost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq * iocg, u64 vtime, u64 abs_cost, struct ioc_now * now)
```

```json
{
  "name": "adjust_inuse_and_calc_cost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_inuse_and_calc_cost",
      "external": false,
      "loc": "block/blk-iocost.c:2426",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585865056,
      "name": "adjust_inuse_and_calc_cost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 704
    },
    {
      "addr": 18446744071594105318,
      "name": "adjust_inuse_and_calc_cost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq * iocg, u64 vtime, u64 abs_cost, struct ioc_now * now)
```

```json
{
  "name": "adjust_inuse_and_calc_cost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_inuse_and_calc_cost",
      "external": false,
      "loc": "block/blk-iocost.c:2433",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586646448,
      "name": "adjust_inuse_and_calc_cost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
    },
    {
      "addr": 18446744071596109612,
      "name": "adjust_inuse_and_calc_cost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq * iocg, u64 vtime, u64 abs_cost, struct ioc_now * now)
```

```json
{
  "name": "adjust_inuse_and_calc_cost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_inuse_and_calc_cost",
      "external": false,
      "loc": "block/blk-iocost.c:2449",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907488,
      "name": "adjust_inuse_and_calc_cost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
    },
    {
      "addr": 18446744071596633520,
      "name": "adjust_inuse_and_calc_cost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
u64 adjust_inuse_and_calc_cost(struct ioc_gq * iocg, u64 vtime, u64 abs_cost, struct ioc_now * now)
```

```json
{
  "name": "adjust_inuse_and_calc_cost",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "adjust_inuse_and_calc_cost",
      "external": false,
      "loc": "block/blk-iocost.c:2456",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185520,
      "name": "adjust_inuse_and_calc_cost",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
    },
    {
      "addr": 18446744071597539838,
      "name": "adjust_inuse_and_calc_cost.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
u64 adjust_inuse_and_calc_cost(struct ioc_gq * iocg, u64 vtime, u64 abs_cost, struct ioc_now * now)
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

# Function: <code>__propagate_weights</code>

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
void __propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "__propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659744,
      "name": "__propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1068",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_incur_debt",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659744,
      "name": "__propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
void __propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "__propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584688032,
      "name": "__propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1064",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_incur_debt",
        "block/blk-iocost.c:iocg_activate",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584688032,
      "name": "__propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void __propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "__propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585110816,
      "name": "__propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1064",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_incur_debt",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585110816,
      "name": "__propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void __propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "__propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585840288,
      "name": "__propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1063",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585840288,
      "name": "__propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
void __propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "__propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586621072,
      "name": "__propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1068",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621072,
      "name": "__propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void __propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "__propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586879376,
      "name": "__propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1084",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586879376,
      "name": "__propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void __propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "__propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587157328,
      "name": "__propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1084",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:weight_updated"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587157328,
      "name": "__propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void __propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
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

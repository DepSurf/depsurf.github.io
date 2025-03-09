# Function: <code>propagate_weights</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584671442,
      "name": "propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1133",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_incur_debt",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584699442,
      "name": "propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1139",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_incur_debt",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585121106,
      "name": "propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1139",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:iocg_incur_debt",
        "block/blk-iocost.c:weight_updated"
      ],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118848,
      "name": "propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071592320547,
      "name": "propagate_weights.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585860181,
      "name": "propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1138",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:weight_updated"
      ],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_incur_debt",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853504,
      "name": "propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071594105034,
      "name": "propagate_weights.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586646201,
      "name": "propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1143",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:weight_updated"
      ],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_incur_debt",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586637136,
      "name": "propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071596109411,
      "name": "propagate_weights.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586904329,
      "name": "propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1159",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:weight_updated"
      ],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_incur_debt",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898128,
      "name": "propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071596633319,
      "name": "propagate_weights.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```

```json
{
  "name": "propagate_weights",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587182361,
      "name": "propagate_weights",
      "external": false,
      "loc": "block/blk-iocost.c:1159",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_pd_free",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:weight_updated"
      ],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_incur_debt",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176160,
      "name": "propagate_weights",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071597539637,
      "name": "propagate_weights.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void propagate_weights(struct ioc_gq * iocg, u32 active, u32 inuse, bool save, struct ioc_now * now)
```
</details>
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

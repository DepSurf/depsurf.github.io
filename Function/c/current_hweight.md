# Function: <code>current_hweight</code>

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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584151344,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:957",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151344,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584548912,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:955",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548912,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584659984,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:1140",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659984,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584688336,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:1146",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584688336,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585111120,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:1146",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111120,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585840608,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:1145",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585840608,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586621408,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:1150",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621408,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586879712,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:1166",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586879712,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587157664,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:1166",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:adjust_inuse_and_calc_cost",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:transfer_surpluses",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_waitq",
        "block/blk-iocost.c:iocg_kick_delay"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587157664,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496002208,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:957",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496002208,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229342696,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:957",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229342696,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290231568,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:957",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290231568,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275097760,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:957",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275097760,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584120080,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:957",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120080,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055744,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:957",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055744,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103840,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:957",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103840,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```

```json
{
  "name": "current_hweight",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207696,
      "name": "current_hweight",
      "external": false,
      "loc": "block/blk-iocost.c:957",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_kick_delay",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207696,
      "name": "current_hweight",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void current_hweight(struct ioc_gq * iocg, u32 * hw_activep, u32 * hw_inusep)
```
</details>
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

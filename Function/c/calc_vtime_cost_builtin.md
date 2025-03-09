# Function: <code>calc_vtime_cost_builtin</code>

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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584151616,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1630",
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
      "addr": 18446744071584151616,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549184,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1648",
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
      "addr": 18446744071584549184,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584660848,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:2469",
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
      "addr": 18446744071584660848,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689200,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:2476",
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
      "addr": 18446744071584689200,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585111408,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:2483",
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
      "addr": 18446744071585111408,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585841104,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:2486",
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
      "addr": 18446744071585841104,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586621936,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:2493",
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
      "addr": 18446744071586621936,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586880240,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:2510",
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
      "addr": 18446744071586880240,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587158192,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:2517",
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
      "addr": 18446744071587158192,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496002456,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1630",
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
      "addr": 18446603336496002456,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229342996,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1630",
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
      "addr": 3229342996,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290231984,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1630",
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
      "addr": 13835058055290231984,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275098174,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1630",
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
      "addr": 18446743936275098174,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584120352,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1630",
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
      "addr": 18446744071584120352,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056016,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1630",
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
      "addr": 18446744071584056016,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584104112,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1630",
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
      "addr": 18446744071584104112,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
```

```json
{
  "name": "calc_vtime_cost_builtin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207968,
      "name": "calc_vtime_cost_builtin",
      "external": false,
      "loc": "block/blk-iocost.c:1630",
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
      "addr": 18446744071584207968,
      "name": "calc_vtime_cost_builtin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void calc_vtime_cost_builtin(struct bio * bio, struct ioc_gq * iocg, bool is_merge, u64 * costp)
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

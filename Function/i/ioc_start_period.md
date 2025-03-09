# Function: <code>ioc_start_period</code>

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
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584157440,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:876",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157440,
      "name": "ioc_start_period.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584552032,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:874",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552032,
      "name": "ioc_start_period",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584662928,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:1050",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662928,
      "name": "ioc_start_period",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584690896,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:1046",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584690896,
      "name": "ioc_start_period",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585113472,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:1046",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585113472,
      "name": "ioc_start_period",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585843488,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:1045",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843488,
      "name": "ioc_start_period",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586624560,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:1050",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586624560,
      "name": "ioc_start_period",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586882960,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:1066",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586882960,
      "name": "ioc_start_period",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587160896,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:1066",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587160896,
      "name": "ioc_start_period",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496006000,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:876",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496006000,
      "name": "ioc_start_period.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229347756,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:876",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229347756,
      "name": "ioc_start_period",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290240304,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:876",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290240304,
      "name": "ioc_start_period.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275102992,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:876",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275102992,
      "name": "ioc_start_period.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584126176,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:876",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126176,
      "name": "ioc_start_period.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584061840,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:876",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061840,
      "name": "ioc_start_period.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109936,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:876",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109936,
      "name": "ioc_start_period.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioc_start_period",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584214704,
      "name": "ioc_start_period",
      "external": false,
      "loc": "block/blk-iocost.c:876",
      "file": "block/blk-iocost.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214704,
      "name": "ioc_start_period.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void ioc_start_period(struct ioc * ioc, struct ioc_now * now)
```
</details>
</li>
</ul>

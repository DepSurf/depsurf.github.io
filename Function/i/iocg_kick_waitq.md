# Function: <code>iocg_kick_waitq</code>

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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584152864,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152864,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584550384,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1140",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584550384,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
void iocg_kick_waitq(struct ioc_gq * iocg, bool pay_debt, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584666080,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1455",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584666080,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 735
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
void iocg_kick_waitq(struct ioc_gq * iocg, bool pay_debt, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584695744,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1462",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695744,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
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
void iocg_kick_waitq(struct ioc_gq * iocg, bool pay_debt, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585118928,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1462",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585118928,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
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
void iocg_kick_waitq(struct ioc_gq * iocg, bool pay_debt, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585853600,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1461",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853600,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
void iocg_kick_waitq(struct ioc_gq * iocg, bool pay_debt, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586637248,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1466",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586637248,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
void iocg_kick_waitq(struct ioc_gq * iocg, bool pay_debt, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586898240,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1482",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586898240,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
void iocg_kick_waitq(struct ioc_gq * iocg, bool pay_debt, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587176272,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1489",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_check_iocgs",
        "block/blk-iocost.c:ioc_forgive_debts",
        "block/blk-iocost.c:iocg_waitq_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587176272,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496012144,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496012144,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229345632,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229345632,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 948
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290233968,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290233968,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275099296,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275099296,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584121600,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584121600,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057264,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057264,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105360,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105360,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_waitq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584209216,
      "name": "iocg_kick_waitq",
      "external": false,
      "loc": "block/blk-iocost.c:1142",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_waitq_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209216,
      "name": "iocg_kick_waitq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
void iocg_kick_waitq(struct ioc_gq * iocg, struct ioc_now * now)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool pay_debt</code>
</li>
<li>
<b>Param reordered. </b>
<code>iocg, now</code> ➡️ <code>iocg, pay_debt, now</code>
</li>
</ul>
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

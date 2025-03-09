# Function: <code>iocg_kick_delay</code>

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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584152400,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1215",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152400,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549968,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1210",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584549968,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584660272,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1320",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584660272,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584688624,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1326",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584688624,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1326",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111680,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
    },
    {
      "addr": 18446744071592320298,
      "name": "iocg_kick_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1325",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841456,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
    },
    {
      "addr": 18446744071594104847,
      "name": "iocg_kick_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1330",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586623776,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
    },
    {
      "addr": 18446744071596109224,
      "name": "iocg_kick_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1346",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586882048,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
    },
    {
      "addr": 18446744071596633092,
      "name": "iocg_kick_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1346",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_merge",
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:iocg_kick_waitq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587160000,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    },
    {
      "addr": 18446744071597539410,
      "name": "iocg_kick_delay.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496010016,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1215",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496010016,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229344716,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1215",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229344716,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290233216,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1215",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290233216,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 752
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275098910,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1215",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275098910,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584121136,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1215",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584121136,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056800,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1215",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056800,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584104896,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1215",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104896,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```

```json
{
  "name": "iocg_kick_delay",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208752,
      "name": "iocg_kick_delay",
      "external": false,
      "loc": "block/blk-iocost.c:1215",
      "file": "block/blk-iocost.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:ioc_rqos_throttle",
        "block/blk-iocost.c:ioc_timer_fn",
        "block/blk-iocost.c:iocg_delay_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208752,
      "name": "iocg_kick_delay",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
bool iocg_kick_delay(struct ioc_gq * iocg, struct ioc_now * now, u64 cost)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 cost</code>
</li>
</ul>
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

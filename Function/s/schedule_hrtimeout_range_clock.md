# Function: <code>schedule_hrtimeout_range_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t * expires, long unsigned int delta, const enum hrtimer_mode mode, int clock)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587379232,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1727",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587379232,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, int clock)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587882144,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1687",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587882144,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, int clock)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588098880,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1687",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098880,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, int clock)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588324592,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1678",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588324592,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, int clock)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588890704,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1684",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890704,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589268960,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1918",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589268960,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589511520,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1908",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589511520,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589970688,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1908",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589970688,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590198240,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2103",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590198240,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591214064,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2110",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout",
        "ipc/mqueue.c:wq_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591214064,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591709200,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2130",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout",
        "ipc/mqueue.c:wq_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591709200,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591656576,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2130",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout",
        "ipc/mqueue.c:wq_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591656576,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592830272,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2278",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout",
        "ipc/mqueue.c:wq_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592830272,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594738528,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2278",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout",
        "ipc/mqueue.c:wq_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594738528,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596490672,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2280",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout",
        "ipc/mqueue.c:wq_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596490672,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597031984,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2283",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout",
        "ipc/mqueue.c:wq_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597031984,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597961376,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2277",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout",
        "ipc/mqueue.c:wq_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597961376,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503945088,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2103",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503945088,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236554088,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2103",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236554088,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297798080,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2103",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297798080,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279808854,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2103",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279808854,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589800528,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2103",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589800528,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589522976,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2103",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589522976,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590243936,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2103",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590243936,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int schedule_hrtimeout_range_clock(ktime_t * expires, u64 delta, const enum hrtimer_mode mode, clockid_t clock_id)
```

```json
{
  "name": "schedule_hrtimeout_range_clock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590294256,
      "name": "schedule_hrtimeout_range_clock",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2103",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590294256,
      "name": "schedule_hrtimeout_range_clock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int delta</code> ➡️ <code>u64 delta</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>clockid_t clock_id</code>
</li>
<li>
<b>Param removed. </b>
<code>int clock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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

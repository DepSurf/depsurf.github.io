# Function: <code>hrtimer_sleeper_start_expires</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590198371,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1782",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123536,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591214191,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1787",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183968,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591709327,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1804",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167856,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591656700,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1804",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173280,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592830396,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1952",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580318864,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594738728,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1952",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/waitwake.c:futex_wait_multiple",
        "kernel/futex/waitwake.c:futex_wait_queue",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580530240,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596490872,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1952",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/waitwake.c:futex_wait_multiple",
        "kernel/futex/waitwake.c:futex_wait_queue",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786384,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597032146,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1955",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/waitwake.c:futex_wait_multiple",
        "kernel/futex/waitwake.c:futex_wait_queue",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868656,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597961538,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1956",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex/pi.c:futex_lock_pi",
        "kernel/futex/waitwake.c:futex_wait_multiple",
        "kernel/futex/waitwake.c:futex_wait_queue",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959632,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503945224,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1782",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491342440,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236554264,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1782",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225335556,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297798228,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1782",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284273168,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279808936,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1782",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271839040,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589800659,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1782",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092736,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589523107,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1782",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038064,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590244067,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1782",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083808,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_sleeper_start_expires",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590294387,
      "name": "hrtimer_sleeper_start_expires",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1782",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait_queue_me"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135520,
      "name": "hrtimer_sleeper_start_expires",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void hrtimer_sleeper_start_expires(struct hrtimer_sleeper * sl, enum hrtimer_mode mode)
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

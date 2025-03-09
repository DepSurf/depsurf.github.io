# Function: <code>hrtimer_init_sleeper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, struct task_struct * task)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822576,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1474",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_wait",
        "kernel/futex.c:futex_lock_pi",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822576,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, struct task_struct * task)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587881667,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1464",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851456,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, struct task_struct * task)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588098403,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1464",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880064,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, struct task_struct * task)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588324055,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1436",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579889376,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, struct task_struct * task)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588890123,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1441",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933888,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, struct task_struct * task)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589269120,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1652",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980832,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, struct task_struct * task)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589511680,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1642",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027488,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, struct task_struct * task)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589970861,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1642",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:do_nanosleep"
      ],
      "caller_func": [
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070432,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121328,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1837",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121328,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580185970,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1842",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181616,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580166704,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1859",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580166704,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170784,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1859",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170784,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592830120,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2007",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317056,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580532406,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2007",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/futex/core.c:futex_setup_timer",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580528912,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580788774,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2007",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/futex/core.c:futex_setup_timer",
        "fs/aio.c:read_events",
        "block/blk-mq.c:blk_mq_poll_hybrid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784992,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580872011,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2010",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/futex/core.c:futex_setup_timer",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868880,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580962507,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2011",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/futex/core.c:futex_setup_timer",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956592,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491339520,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1837",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491339520,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225332244,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1837",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225332244,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284269648,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1837",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284269648,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271836514,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1837",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271836514,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090528,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1837",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090528,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580035856,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1837",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035856,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580081600,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1837",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081600,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void hrtimer_init_sleeper(struct hrtimer_sleeper * sl, clockid_t clock_id, enum hrtimer_mode mode)
```

```json
{
  "name": "hrtimer_init_sleeper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133136,
      "name": "hrtimer_init_sleeper",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1837",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:schedule_hrtimeout_range_clock",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep",
        "kernel/time/hrtimer.c:hrtimer_nanosleep_restart",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:futex_wait",
        "fs/aio.c:read_events"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133136,
      "name": "hrtimer_init_sleeper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>clockid_t clock_id</code>
</li>
<li>
<b>Param added. </b>
<code>enum hrtimer_mode mode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
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

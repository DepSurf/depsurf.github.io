# Function: <code>schedule_hrtimeout_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int schedule_hrtimeout_range(ktime_t * expires, long unsigned int delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587379664,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1795",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:poll_schedule_timeout",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587379664,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587882616,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1755",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:poll_schedule_timeout",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587882576,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588099352,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1759",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:poll_schedule_timeout",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588099312,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588325032,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1750",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:poll_schedule_timeout",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588324992,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588891144,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1756",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:poll_schedule_timeout",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588891104,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589269413,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1990",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589269376,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589511973,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1980",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589511936,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589971141,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:1980",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589971104,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590198549,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2172",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590198512,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591214389,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2179",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591214352,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591709528,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2199",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591709488,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591656904,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2199",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591656864,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592830600,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2347",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range_state",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592830560,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594738888,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2348",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range_state",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll",
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594738832,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596491064,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2350",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range_state",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll",
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596490992,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597032408,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2361",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range_state",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll",
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597032336,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597961800,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2355",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range_state",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll",
        "ipc/sem.c:__do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597961728,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503945460,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2172",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503945360,
      "name": "schedule_hrtimeout_range",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236554500,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2172",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:do_sigtimedwait",
        "kernel/time/timer.c:usleep_range",
        "fs/eventpoll.c:do_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236554428,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297798464,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2172",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297798416,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279809146,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2172",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/signal.c:__se_sys_rt_sigtimedwait",
        "kernel/time/timer.c:usleep_range",
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select",
        "fs/eventpoll.c:do_epoll_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279809060,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589800837,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2172",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589800800,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589523285,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2172",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589523248,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590244245,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2172",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590244208,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int schedule_hrtimeout_range(ktime_t * expires, u64 delta, const enum hrtimer_mode mode)
```

```json
{
  "name": "schedule_hrtimeout_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590294565,
      "name": "schedule_hrtimeout_range",
      "external": true,
      "loc": "kernel/time/hrtimer.c:2172",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:schedule_hrtimeout"
      ],
      "caller_func": [
        "kernel/time/timer.c:usleep_range",
        "fs/eventpoll.c:ep_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590294528,
      "name": "schedule_hrtimeout_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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

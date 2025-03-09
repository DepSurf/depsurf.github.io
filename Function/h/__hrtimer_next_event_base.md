# Function: <code>__hrtimer_next_event_base</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981024,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:492",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981024,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027680,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:483",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027680,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070704,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:482",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070704,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120080,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120080,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580180640,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180640,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165568,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:502",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165568,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170144,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:502",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170144,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:502",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315504,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071592151354,
      "name": "__hrtimer_next_event_base.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:502",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526560,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071593926341,
      "name": "__hrtimer_next_event_base.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:502",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782480,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071595994518,
      "name": "__hrtimer_next_event_base.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:504",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865488,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071596512837,
      "name": "__hrtimer_next_event_base.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:504",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimers_cpu_dying",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955984,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071597412164,
      "name": "__hrtimer_next_event_base.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491337744,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491337744,
      "name": "__hrtimer_next_event_base",
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225331084,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225331084,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284267296,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284267296,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271835414,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271835414,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089280,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089280,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034608,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034608,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080352,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080352,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```

```json
{
  "name": "__hrtimer_next_event_base",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131856,
      "name": "__hrtimer_next_event_base",
      "external": false,
      "loc": "kernel/time/hrtimer.c:503",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:hrtimer_next_event_without",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131856,
      "name": "__hrtimer_next_event_base",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
ktime_t __hrtimer_next_event_base(struct hrtimer_cpu_base * cpu_base, const struct hrtimer * exclude, unsigned int active, ktime_t expires_next)
```
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

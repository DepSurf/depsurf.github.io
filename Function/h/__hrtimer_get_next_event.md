# Function: <code>__hrtimer_get_next_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579822464,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:469",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822464,
      "name": "__hrtimer_get_next_event",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579851344,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:465",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:__remove_hrtimer",
        "kernel/time/hrtimer.c:retrigger_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851344,
      "name": "__hrtimer_get_next_event",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579884195,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:465",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579893024,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:466",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579937552,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:466",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981248,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:556",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981248,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027904,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:547",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027904,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070928,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:546",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070928,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580120304,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120304,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580187631,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180864,
      "name": "__hrtimer_get_next_event",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580172402,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:569",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165792,
      "name": "__hrtimer_get_next_event",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580176898,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:569",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_run_softirq"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170352,
      "name": "__hrtimer_get_next_event",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580322395,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:569",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580315712,
      "name": "__hrtimer_get_next_event",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580534205,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:569",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526784,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580790669,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:569",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782720,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580873917,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:571",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_dead_cpu",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865760,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580964419,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:571",
      "file": "kernel/time/hrtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/hrtimer.c:hrtimers_cpu_dying",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_update_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_next_event"
      ],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_get_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956256,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491337992,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491337992,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225331340,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225331340,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284267680,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284267680,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271835564,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_run_softirq",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271835564,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089504,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089504,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034832,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034832,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080576,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080576,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
```

```json
{
  "name": "__hrtimer_get_next_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132080,
      "name": "__hrtimer_get_next_event",
      "external": false,
      "loc": "kernel/time/hrtimer.c:567",
      "file": "kernel/time/hrtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/hrtimer.c:hrtimer_interrupt",
        "kernel/time/hrtimer.c:hrtimer_get_next_event",
        "kernel/time/hrtimer.c:hrtimer_update_softirq_timer",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram",
        "kernel/time/hrtimer.c:hrtimer_force_reprogram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132080,
      "name": "__hrtimer_get_next_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
ktime_t __hrtimer_get_next_event(struct hrtimer_cpu_base * cpu_base, unsigned int active_mask)
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

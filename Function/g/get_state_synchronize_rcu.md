# Function: <code>get_state_synchronize_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787936,
      "name": "get_state_synchronize_rcu",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3328",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814048,
      "name": "get_state_synchronize_rcu",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3326",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842592,
      "name": "get_state_synchronize_rcu",
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579837584,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3346",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837584,
      "name": "get_state_synchronize_rcu",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877904,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3329",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877904,
      "name": "get_state_synchronize_rcu",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912224,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3135",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912224,
      "name": "get_state_synchronize_rcu",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959808,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2980",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959808,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998656,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2689",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998656,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580048720,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2749",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048720,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104256,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3444",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104256,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580085472,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3754",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580085472,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580097013,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3799",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu"
      ],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087056,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580236309,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3760",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu"
      ],
      "caller_func": [
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580223680,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580390181,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3856",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu"
      ],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/events/core.c:ring_buffer_attach",
        "net/sched/sch_generic.c:mini_qdisc_pair_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580385200,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580615669,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3593",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu"
      ],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/events/core.c:ring_buffer_attach",
        "net/sched/sch_generic.c:mini_qdisc_pair_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612368,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580689349,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3585",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu",
        "kernel/rcu/tree.c:kvfree_call_rcu"
      ],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/events/core.c:ring_buffer_attach",
        "net/sched/sch_generic.c:mini_qdisc_pair_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580686208,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580756277,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:3657",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu",
        "kernel/rcu/tree.c:kvfree_call_rcu"
      ],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/events/core.c:ring_buffer_attach",
        "net/sched/sch_generic.c:mini_qdisc_pair_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753024,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491252992,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2749",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491252992,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225263812,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2749",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225263812,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284155696,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2749",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284155696,
      "name": "get_state_synchronize_rcu",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271778960,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2749",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271778960,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580017456,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2749",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017456,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956112,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2749",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956112,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008992,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2749",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008992,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
long unsigned int get_state_synchronize_rcu()
```

```json
{
  "name": "get_state_synchronize_rcu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055856,
      "name": "get_state_synchronize_rcu",
      "external": true,
      "loc": "kernel/rcu/tree.c:2749",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:ring_buffer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055856,
      "name": "get_state_synchronize_rcu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
long unsigned int get_state_synchronize_rcu()
```
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

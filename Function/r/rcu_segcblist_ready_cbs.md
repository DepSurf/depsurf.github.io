# Function: <code>rcu_segcblist_ready_cbs</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579857653,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:120",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_extract_done_cbs",
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_dequeue"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_check_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857056,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899039,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:92",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_check_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579897984,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579932972,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:92",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_check_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931904,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980028,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:92",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_check_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978960,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580020524,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:79",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580019456,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580071503,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:193",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070256,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580129040,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:182",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_pending",
        "kernel/rcu/tree.c:rcu_pending",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580129040,
      "name": "rcu_segcblist_ready_cbs",
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580107232,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:182",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_pending",
        "kernel/rcu/tree.c:rcu_pending",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107232,
      "name": "rcu_segcblist_ready_cbs",
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580110816,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:280",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110816,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580252128,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:280",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252128,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580420704,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:278",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420704,
      "name": "rcu_segcblist_ready_cbs",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580660464,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:278",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580660464,
      "name": "rcu_segcblist_ready_cbs",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580736656,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:278",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736656,
      "name": "rcu_segcblist_ready_cbs",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580821680,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:278",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_need_gpcb",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:show_rcu_nocb_state",
        "kernel/rcu/tree.c:nocb_cb_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:__call_rcu_nocb_wake",
        "kernel/rcu/tree.c:rcu_pending",
        "kernel/rcu/tree.c:rcu_pending",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821680,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491284652,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:193",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491282888,
      "name": "rcu_segcblist_ready_cbs",
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225291756,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:193",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225290120,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284189448,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:193",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284187808,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271801668,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:193",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271800370,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580040239,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:193",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038992,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579985565,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:193",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:show_rcu_gp_kthreads",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984400,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580031775,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:193",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030528,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```

```json
{
  "name": "rcu_segcblist_ready_cbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580082479,
      "name": "rcu_segcblist_ready_cbs",
      "external": true,
      "loc": "kernel/rcu/rcu_segcblist.c:193",
      "file": "kernel/rcu/rcu_segcblist.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge"
      ],
      "caller_func": [
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/srcutree.c:srcu_invoke_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580081232,
      "name": "rcu_segcblist_ready_cbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist * rsclp)
```
</details>
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

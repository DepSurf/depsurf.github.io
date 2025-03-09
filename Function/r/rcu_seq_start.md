# Function: <code>rcu_seq_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579781760,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/tree.c:3348",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/rcu/tree.c:synchronize_sched_expedited"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:_rcu_barrier",
        "kernel/rcu/tree.c:synchronize_sched_expedited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781760,
      "name": "rcu_seq_start.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void rcu_seq_start(long unsigned int * sp)
```

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579807312,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/tree.c:3426",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:_rcu_barrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807312,
      "name": "rcu_seq_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void rcu_seq_start(long unsigned int * sp)
```

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579836960,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/tree.c:3424",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:_rcu_barrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836960,
      "name": "rcu_seq_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579833811,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:96",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579845894,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:96",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier"
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
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579874102,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:96",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579886553,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:96",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579908182,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:73",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915002,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:73",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:_rcu_barrier"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579955569,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:73",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579968647,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:73",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579995859,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005496,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580045987,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580055587,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580099656,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580120762,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_gp_init"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580081208,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580101866,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_gp_init"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580082568,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580102474,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_gp_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580218936,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580242393,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:rcu_gp_init"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580369480,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:57",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381554,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:57",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388087,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:57",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:rcu_gp_init"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580589053,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:56",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_one_gp",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580608610,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:56",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580627255,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:56",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_poll_gp_seq_start_unlocked"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580662509,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:93",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_one_gp",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580682327,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:93",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580701351,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:93",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_poll_gp_seq_start_unlocked"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580729323,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:94",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_one_gp",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580749111,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:94",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580767287,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:94",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:exp_funnel_lock",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_poll_gp_seq_start_unlocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491246856,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491269504,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225258980,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3225271520,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_init",
        "kernel/rcu/tree.c:rcu_gp_init"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284151340,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284166292,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271774356,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271786970,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580014723,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580024323,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579953443,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579965443,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580006259,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580015859,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580051923,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_start",
        "kernel/rcu/srcutree.c:srcu_gp_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580060759,
      "name": "rcu_seq_start",
      "external": false,
      "loc": "kernel/rcu/rcu.h:55",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void rcu_seq_start(long unsigned int * sp)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void rcu_seq_start(long unsigned int * sp)
```
</details>
</li>
</ul>

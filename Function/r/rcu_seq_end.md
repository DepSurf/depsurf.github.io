# Function: <code>rcu_seq_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579781808,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/tree.c:3356",
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
      "addr": 18446744071579781808,
      "name": "rcu_seq_end.part.47",
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
void rcu_seq_end(long unsigned int * sp)
```

```json
{
  "name": "rcu_seq_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579807376,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/tree.c:3434",
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
      "addr": 18446744071579807376,
      "name": "rcu_seq_end",
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
void rcu_seq_end(long unsigned int * sp)
```

```json
{
  "name": "rcu_seq_end",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579837024,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/tree.c:3432",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:_rcu_barrier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837024,
      "name": "rcu_seq_end",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579835023,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:104",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579840321,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:104",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579875327,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:104",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579884161,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:104",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579909394,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:87",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579920263,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:87",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579956946,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:87",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579965053,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:87",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579997218,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580004022,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580047346,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580054196,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580099916,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121316,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup"
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580081468,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580102436,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup"
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580082828,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580099732,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup"
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580219209,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580239990,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup"
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580369526,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:71",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381769,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:71",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580412964,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:71",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup"
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580589099,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:70",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_one_gp",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580608845,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:70",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580632768,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:70",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_poll_gp_seq_end_unlocked"
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580662555,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:107",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_one_gp",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580682564,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:107",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714960,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:107",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_poll_gp_seq_end_unlocked"
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580729365,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:108",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_one_gp",
        "kernel/rcu/update.c:rcu_barrier_tasks_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580749348,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:108",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580788800,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:108",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_gp_cleanup",
        "kernel/rcu/tree.c:rcu_poll_gp_seq_end_unlocked"
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491248548,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491259416,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225259312,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:srcu_barrier",
        "kernel/rcu/srcutree.c:srcu_gp_end"
      ],
      "caller_func": []
    },
    {
      "addr": 3225269400,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284153744,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284162048,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271777520,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271785930,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580016082,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022932,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579954774,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579964196,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580007618,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014468,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
  "name": "rcu_seq_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580053068,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:process_srcu",
        "kernel/rcu/srcutree.c:srcu_barrier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059300,
      "name": "rcu_seq_end",
      "external": false,
      "loc": "kernel/rcu/rcu.h:69",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
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
void rcu_seq_end(long unsigned int * sp)
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
void rcu_seq_end(long unsigned int * sp)
```
</details>
</li>
</ul>

# Function: <code>rcu_report_exp_cpu_mult</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579782992,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree.c:3562",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_sched_expedited",
        "kernel/rcu/tree.c:rcu_cpu_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782992,
      "name": "rcu_report_exp_cpu_mult.constprop.73",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579809744,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:202",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579809744,
      "name": "rcu_report_exp_cpu_mult.constprop.79",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void rcu_report_exp_cpu_mult(struct rcu_state * rsp, struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579834288,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:202",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834288,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_state * rsp, struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579838016,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:218",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838016,
      "name": "rcu_report_exp_cpu_mult",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_state * rsp, struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579878352,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:218",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878352,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
void rcu_report_exp_cpu_mult(struct rcu_state * rsp, struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915424,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:245",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915424,
      "name": "rcu_report_exp_cpu_mult",
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962496,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:244",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962496,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002032,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002032,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052224,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052224,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580108736,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:230",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108736,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580090976,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:230",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090976,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580092320,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:230",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092320,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580230496,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:230",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead",
        "kernel/rcu/tree.c:rcu_softirq_qs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580230496,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580391552,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:230",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_preempt_ctxt_queue",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391552,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635904,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:232",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_preempt_ctxt_queue",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635904,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705408,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:233",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_preempt_ctxt_queue",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705408,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:232",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_preempt_ctxt_queue",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772128,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
    },
    {
      "addr": 18446744071597407107,
      "name": "rcu_report_exp_cpu_mult.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491260344,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491260344,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225264092,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225264092,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284156192,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_qs",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284156192,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271783450,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271783450,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580020960,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580020960,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962096,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962096,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012496,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012496,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void rcu_report_exp_cpu_mult(struct rcu_node * rnp, long unsigned int mask, bool wake)
```

```json
{
  "name": "rcu_report_exp_cpu_mult",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056496,
      "name": "rcu_report_exp_cpu_mult",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:234",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_note_context_switch",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_report_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056496,
      "name": "rcu_report_exp_cpu_mult",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_state * rsp, struct rcu_node * rnp, long unsigned int mask, bool wake)
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct rcu_state * rsp</code>
</li>
<li>
<b>Param reordered. </b>
<code>rsp, rnp, mask, wake</code> ➡️ <code>rnp, mask, wake</code>
</li>
</ul>
</details>
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

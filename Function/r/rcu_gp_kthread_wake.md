# Function: <code>rcu_gp_kthread_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_gp_kthread_wake(struct rcu_state * rsp)
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579780960,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1608",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780960,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void rcu_gp_kthread_wake(struct rcu_state * rsp)
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805872,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1716",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805872,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void rcu_gp_kthread_wake(struct rcu_state * rsp)
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579833872,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1718",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579833872,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void rcu_gp_kthread_wake(struct rcu_state * rsp)
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579837616,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1792",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579837616,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void rcu_gp_kthread_wake(struct rcu_state * rsp)
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877952,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1864",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877952,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void rcu_gp_kthread_wake(struct rcu_state * rsp)
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579912352,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1724",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912352,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959936,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1573",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_process_callbacks",
        "kernel/rcu/tree.c:force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959936,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999952,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1225",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999952,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580050144,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050144,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580105408,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1433",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105408,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580086848,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1513",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rdp",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086848,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580088224,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1517",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088224,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580225744,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1470",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225744,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580389776,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1486",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389776,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580616880,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1061",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_common",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616880,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580690560,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1021",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_common",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690560,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580764208,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1063",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore",
        "kernel/rcu/tree.c:nocb_cb_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:start_poll_synchronize_rcu_common",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764208,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491253336,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491253336,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225269720,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225269720,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284162496,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284162496,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271781144,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271781144,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580018880,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018880,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579957360,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957360,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580010416,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rnp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010416,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void rcu_gp_kthread_wake()
```

```json
{
  "name": "rcu_gp_kthread_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580061392,
      "name": "rcu_gp_kthread_wake",
      "external": false,
      "loc": "kernel/rcu/tree.c:1233",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcutree_migrate_callbacks",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_force_quiescent_state",
        "kernel/rcu/tree.c:rcu_report_qs_rsp",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061392,
      "name": "rcu_gp_kthread_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct rcu_state * rsp</code>
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

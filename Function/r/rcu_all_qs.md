# Function: <code>rcu_all_qs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788720,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree.c:377",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_check_callbacks"
      ],
      "caller_func": [
        "kernel/workqueue.c:process_one_work",
        "mm/mlock.c:apply_mlockall_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788720,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813280,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree.c:368",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:process_one_work",
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "mm/mlock.c:apply_mlockall_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813280,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579839920,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree.c:369",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:process_one_work",
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "mm/mlock.c:apply_mlockall_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839920,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579842910,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree.c:490",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": [
        "kernel/workqueue.c:process_one_work",
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "mm/mlock.c:apply_mlockall_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842560,
      "name": "rcu_all_qs.part.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071579842688,
      "name": "rcu_all_qs",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579882401,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree.c:487",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ],
      "caller_func": [
        "kernel/workqueue.c:process_one_work",
        "kernel/rcu/tree.c:force_qs_rnp",
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "mm/mlock.c:apply_mlockall_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882064,
      "name": "rcu_all_qs.part.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071579882192,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579918464,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree.c:474",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched",
        "kernel/rcu/tree.c:rcu_check_callbacks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918464,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579962768,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:979",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962768,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580011600,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:837",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011600,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580062176,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:818",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062176,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580117344,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:807",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117344,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580097232,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:835",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:affine_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097232,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580105120,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:902",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:affine_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105120,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580247285,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:862",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:affine_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592146353,
      "name": "rcu_all_qs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580247232,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491271968,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:818",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491271968,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225272536,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:818",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225272536,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284167936,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:818",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284167936,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271783848,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:818",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271783848,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580030912,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:818",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030912,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579962416,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:818",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962416,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void rcu_all_qs()
```

```json
{
  "name": "rcu_all_qs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580022448,
      "name": "rcu_all_qs",
      "external": true,
      "loc": "kernel/rcu/tree_plugin.h:818",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:_cond_resched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022448,
      "name": "rcu_all_qs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void rcu_all_qs()
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➖</summary>

```c
void rcu_all_qs()
```
</details>
</li>
</ul>

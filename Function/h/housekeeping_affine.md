# Function: <code>housekeeping_affine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_affine",
      "external": false,
      "loc": "include/linux/tick.h:191",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_affine",
      "external": false,
      "loc": "include/linux/tick.h:282",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "housekeeping_affine",
      "external": false,
      "loc": "include/linux/tick.h:282",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_affine",
      "external": false,
      "loc": "include/linux/tick.h:280",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "housekeeping_affine",
      "external": false,
      "loc": "include/linux/tick.h:280",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "housekeeping_affine",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "housekeeping_affine",
      "external": false,
      "loc": "include/linux/tick.h:281",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "housekeeping_affine",
      "external": false,
      "loc": "include/linux/tick.h:281",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579746384,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:39",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746384,
      "name": "housekeeping_affine",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579780752,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:34",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780752,
      "name": "housekeeping_affine",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579823632,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:34",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579823632,
      "name": "housekeeping_affine",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579851840,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:41",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579851840,
      "name": "housekeeping_affine",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900368,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900368,
      "name": "housekeeping_affine",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579943520,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943520,
      "name": "housekeeping_affine",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579931776,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931776,
      "name": "housekeeping_affine",
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
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939616,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939616,
      "name": "housekeeping_affine",
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
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580064624,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580064624,
      "name": "housekeeping_affine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_type type)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580150018,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:65",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593880672,
      "name": "housekeeping_affine.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580149984,
      "name": "housekeeping_affine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_type type)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580323522,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:65",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595981883,
      "name": "housekeeping_affine.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580323488,
      "name": "housekeeping_affine",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_type type)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580390997,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:65",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596500059,
      "name": "housekeeping_affine.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580390928,
      "name": "housekeeping_affine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_type type)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580447125,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:65",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597397421,
      "name": "housekeeping_affine.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580447056,
      "name": "housekeeping_affine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491099544,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491099544,
      "name": "housekeeping_affine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225102904,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225102904,
      "name": "housekeeping_affine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283989904,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283989904,
      "name": "housekeeping_affine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271681724,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271681724,
      "name": "housekeeping_affine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872480,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872480,
      "name": "housekeeping_affine",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579807488,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread",
        "kernel/rcu/tree.c:rcu_gp_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807488,
      "name": "housekeeping_affine",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579860640,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860640,
      "name": "housekeeping_affine",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```

```json
{
  "name": "housekeeping_affine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579906016,
      "name": "housekeeping_affine",
      "external": true,
      "loc": "kernel/sched/isolation.c:49",
      "file": "kernel/sched/isolation.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/update.c:rcu_tasks_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906016,
      "name": "housekeeping_affine",
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void housekeeping_affine(struct task_struct * t, enum hk_flags flags)
```
</details>
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hk_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>enum hk_flags flags</code>
</li>
</ul>
</details>
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

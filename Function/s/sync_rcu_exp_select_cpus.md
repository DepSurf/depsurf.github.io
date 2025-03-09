# Function: <code>sync_rcu_exp_select_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579783560,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree.c:3698",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_sched_expedited"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579810338,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:341",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void sync_rcu_exp_select_cpus(struct rcu_state * rsp, smp_call_func_t func)
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835472,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:341",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835472,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1039
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
void sync_rcu_exp_select_cpus(struct rcu_state * rsp, smp_call_func_t func)
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579839040,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:359",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839040,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1060
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
void sync_rcu_exp_select_cpus(struct rcu_state * rsp, smp_call_func_t func)
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879408,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:359",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879408,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
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
void sync_rcu_exp_select_cpus(struct rcu_state * rsp, smp_call_func_t func)
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916992,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:472",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916992,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
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
void sync_rcu_exp_select_cpus(smp_call_func_t func)
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579963872,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:429",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963872,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580003248,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:421",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003248,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053408,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053408,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109888,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:423",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109888,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580092128,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:423",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580092128,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 487
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580093664,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:423",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093664,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 729
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:424",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231920,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
    },
    {
      "addr": 18446744071592144270,
      "name": "sync_rcu_exp_select_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:529",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396976,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
    },
    {
      "addr": 18446744071593916231,
      "name": "sync_rcu_exp_select_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:531",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580638192,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
    },
    {
      "addr": 18446744071595991304,
      "name": "sync_rcu_exp_select_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:532",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707696,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
    },
    {
      "addr": 18446744071596509336,
      "name": "sync_rcu_exp_select_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:531",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773840,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
    },
    {
      "addr": 18446744071597407189,
      "name": "sync_rcu_exp_select_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491268160,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491268160,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225268612,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225268612,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284160912,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284160912,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271784826,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271784826,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022144,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022144,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579963376,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963376,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013680,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013680,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
void sync_rcu_exp_select_cpus()
```

```json
{
  "name": "sync_rcu_exp_select_cpus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058512,
      "name": "sync_rcu_exp_select_cpus",
      "external": false,
      "loc": "kernel/rcu/tree_exp.h:419",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited",
        "kernel/rcu/tree.c:wait_rcu_exp_gp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058512,
      "name": "sync_rcu_exp_select_cpus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
void sync_rcu_exp_select_cpus(struct rcu_state * rsp, smp_call_func_t func)
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
<code>rsp, func</code> ➡️ <code>func</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>smp_call_func_t func</code>
</li>
</ul>
</details>
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

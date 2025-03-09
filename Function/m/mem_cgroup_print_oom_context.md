# Function: <code>mem_cgroup_print_oom_context</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581580397,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1304",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580397,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1501",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691497,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071581682768,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1512",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764926,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071581755168,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1477",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983637,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071581974928,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1658",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591336913,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071582024528,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1481",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591279598,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071582051040,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1533",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592225078,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071582357856,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1550",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594004154,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071582849424,
      "name": "mem_cgroup_print_oom_context",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583395408,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1610",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583395408,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583614640,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1642",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583614640,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583809536,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1714",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583809536,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493208784,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1512",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493208784,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226839460,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1512",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226839460,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286717312,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1512",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286717312,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272986000,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1512",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272986000,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1512",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733662,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071581723904,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1512",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672302,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071581662704,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1512",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724974,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071581715216,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_print_oom_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_print_oom_context",
      "external": true,
      "loc": "mm/memcontrol.c:1512",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:dump_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793182,
      "name": "mem_cgroup_print_oom_context.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071581782768,
      "name": "mem_cgroup_print_oom_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup * memcg, struct task_struct * p)
```
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

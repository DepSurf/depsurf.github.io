# Function: <code>find_lock_task_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580485584,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:102",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:dump_header",
        "mm/oom_kill.c:oom_kill_process",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485584,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567888,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:107",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:oom_reaper",
        "mm/oom_kill.c:__oom_reap_task",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567888,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635712,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:107",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:oom_kill_process",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635712,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580667744,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:110",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580667744,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580752752,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:112",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580752752,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887456,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:112",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887456,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580960832,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:120",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:dump_header",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960832,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581056048,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581056048,
      "name": "find_lock_task_mm",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111744,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111744,
      "name": "find_lock_task_mm",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581296501,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:133",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298432,
      "name": "find_lock_task_mm",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339296,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:135",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339296,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358592,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:135",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358592,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581606448,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:136",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606448,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581970522,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:133",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_badness"
      ],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967840,
      "name": "find_lock_task_mm",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582401450,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:133",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_badness"
      ],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403968,
      "name": "find_lock_task_mm",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582607482,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:133",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_badness"
      ],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609984,
      "name": "find_lock_task_mm",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582777738,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:133",
      "file": "mm/oom_kill.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/oom_kill.c:oom_badness"
      ],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582781552,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492479184,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492479184,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226353660,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226353660,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285763792,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285763792,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272545350,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272545350,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581080592,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080592,
      "name": "find_lock_task_mm",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581027776,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027776,
      "name": "find_lock_task_mm",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071792,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071792,
      "name": "find_lock_task_mm",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct task_struct * find_lock_task_mm(struct task_struct * p)
```

```json
{
  "name": "find_lock_task_mm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581133392,
      "name": "find_lock_task_mm",
      "external": true,
      "loc": "mm/oom_kill.c:132",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:clear_tasks_mm_cpumask",
        "mm/oom_kill.c:__oom_kill_process",
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133392,
      "name": "find_lock_task_mm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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

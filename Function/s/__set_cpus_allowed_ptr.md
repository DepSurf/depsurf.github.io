# Function: <code>__set_cpus_allowed_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546880,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1205",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546880,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558304,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1123",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558304,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583232,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1134",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583232,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566800,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1059",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566800,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579596544,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1074",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596544,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628176,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1071",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628176,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579665808,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1066",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665808,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1509",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579697040,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071579714965,
      "name": "__set_cpus_allowed_ptr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737872,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1629",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737872,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773904,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1694",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773904,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, u32 flags)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763504,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:2326",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:migrate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763504,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, u32 flags)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579771216,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:2347",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:migrate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771216,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, u32 flags)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579878360,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:2841",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:migrate_enable"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592107403,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, u32 flags)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579994591,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:2940",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:migrate_enable"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593875144,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int __set_cpus_allowed_ptr(struct task_struct * p, struct affinity_context * ctx)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580138384,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:2998",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:migrate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580138384,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
int __set_cpus_allowed_ptr(struct task_struct * p, struct affinity_context * ctx)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217520,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:3174",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:migrate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217520,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
int __set_cpus_allowed_ptr(struct task_struct * p, struct affinity_context * ctx)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580266320,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:3204",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:__sched_setaffinity",
        "kernel/sched/core.c:force_compatible_cpus_allowed_ptr",
        "kernel/sched/core.c:migrate_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580266320,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490916072,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1629",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490916072,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224934084,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1629",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224934084,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283764544,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1629",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283764544,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 796
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271553754,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1629",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271553754,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579714496,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1629",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714496,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642384,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1629",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642384,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579701760,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1629",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701760,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
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
int __set_cpus_allowed_ptr(struct task_struct * p, const struct cpumask * new_mask, bool check)
```

```json
{
  "name": "__set_cpus_allowed_ptr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579745136,
      "name": "__set_cpus_allowed_ptr",
      "external": false,
      "loc": "kernel/sched/core.c:1629",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_setaffinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745136,
      "name": "__set_cpus_allowed_ptr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool check</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct affinity_context * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cpumask * new_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
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

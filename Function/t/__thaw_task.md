# Function: <code>__thaw_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803056,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:149",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803056,
      "name": "__thaw_task",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831040,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:149",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831040,
      "name": "__thaw_task",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860064,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:149",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup_freezer.c:freezer_apply_state",
        "kernel/cgroup_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860064,
      "name": "__thaw_task",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579867952,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:149",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/freezer.c:freezer_apply_state",
        "kernel/cgroup/freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867952,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911680,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:149",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/freezer.c:unfreeze_cgroup",
        "kernel/cgroup/freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911680,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956224,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:149",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/freezer.c:unfreeze_cgroup",
        "kernel/cgroup/freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956224,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002880,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:151",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/freezer.c:unfreeze_cgroup",
        "kernel/cgroup/freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002880,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045632,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:152",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045632,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094720,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094720,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157136,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157136,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141632,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141632,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146320,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146320,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580290064,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580290064,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580498336,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580498336,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580750704,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:194",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750704,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833248,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:194",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833248,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922768,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:197",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922768,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491304064,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491304064,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225302020,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:freezer_apply_state",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225302020,
      "name": "__thaw_task",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284229024,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284229024,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271814928,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271814928,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063920,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063920,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008768,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008768,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054992,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054992,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void __thaw_task(struct task_struct * p)
```

```json
{
  "name": "__thaw_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105744,
      "name": "__thaw_task",
      "external": true,
      "loc": "kernel/freezer.c:146",
      "file": "kernel/freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/cgroup/legacy_freezer.c:unfreeze_cgroup",
        "kernel/cgroup/legacy_freezer.c:freezer_attach",
        "mm/oom_kill.c:mark_oom_victim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105744,
      "name": "__thaw_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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

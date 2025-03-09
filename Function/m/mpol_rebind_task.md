# Function: <code>mpol_rebind_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new, enum mpol_rebind_step step)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816032,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:431",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816032,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new, enum mpol_rebind_step step)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580941456,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:428",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941456,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new, enum mpol_rebind_step step)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013936,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:430",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:cpuset_change_task_nodemask",
        "kernel/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013936,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581061344,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:365",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061344,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581172432,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581172432,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317200,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317200,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581401344,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581401344,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581513488,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581513488,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577856,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577856,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787584,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:393",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787584,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832528,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:393",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832528,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581863376,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:393",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581863376,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582154704,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:366",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582154704,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582609968,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:370",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609968,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583132944,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:370",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132944,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583343184,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:370",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583343184,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583579360,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:372",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583579360,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493015168,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493015168,
      "name": "mpol_rebind_task",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "mpol_rebind_task",
      "external": false,
      "loc": "include/linux/mempolicy.h:262",
      "file": "kernel/cgroup/cpuset.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286441712,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286441712,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "mpol_rebind_task",
      "external": false,
      "loc": "include/linux/mempolicy.h:262",
      "file": "kernel/cgroup/cpuset.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546592,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546592,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488240,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488240,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581537904,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581537904,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```

```json
{
  "name": "mpol_rebind_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581602944,
      "name": "mpol_rebind_task",
      "external": true,
      "loc": "mm/mempolicy.c:367",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_change_task_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602944,
      "name": "mpol_rebind_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum mpol_rebind_step step</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mpol_rebind_task(struct task_struct * tsk, const nodemask_t * new)
```
</details>
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

# Function: <code>cpuset_change_task_nodemask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580005936,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cpuset.c:1032",
      "file": "kernel/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:update_tasks_nodemask",
        "kernel/cpuset.c:cpuset_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005936,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038464,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cpuset.c:1043",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038464,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580070432,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cpuset.c:1043",
      "file": "kernel/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpuset.c:cpuset_attach",
        "kernel/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070432,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580075344,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1047",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580075344,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128128,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1058",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128128,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580189776,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1059",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189776,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580237680,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1582",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237680,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288192,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1543",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288192,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580336528,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1617",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580336528,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580410048,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1619",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410048,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580397360,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1642",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580397360,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580403632,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1642",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403632,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580566336,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1693",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566336,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580761584,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1731",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761584,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581039536,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1920",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581039536,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581127632,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1955",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach_task",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581127632,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226656,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:2736",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach_task",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226656,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491601992,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1617",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491601992,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225558264,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1617",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225558264,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284584432,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1617",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284584432,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272006552,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1617",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272006552,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305328,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1617",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305328,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252672,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1617",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252672,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580296576,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1617",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580296576,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
void cpuset_change_task_nodemask(struct task_struct * tsk, nodemask_t * newmems)
```

```json
{
  "name": "cpuset_change_task_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580351232,
      "name": "cpuset_change_task_nodemask",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1617",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_attach",
        "kernel/cgroup/cpuset.c:update_tasks_nodemask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351232,
      "name": "cpuset_change_task_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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

# Function: <code>sched_change_group</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579542704,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7797",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542704,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579567536,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7950",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567536,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579552464,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:6164",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552464,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581296,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:6232",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581296,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579611856,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:6352",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611856,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579648352,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:6333",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648352,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672416,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:6808",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672416,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579709808,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7011",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579709808,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579749584,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7245",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579749584,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579735360,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:8210",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579735360,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579745424,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:8579",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579745424,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579828000,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:9817",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828000,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579947744,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:10140",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947744,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580164475,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:10320",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580212845,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:10480",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580261526,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:10444",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490890480,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7011",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490890480,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224906340,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7011",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224906340,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283729856,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7011",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283729856,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271539960,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7011",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271539960,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579686032,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7011",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686032,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579614448,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7011",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614448,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579683184,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7011",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683184,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
void sched_change_group(struct task_struct * tsk, int type)
```

```json
{
  "name": "sched_change_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579718400,
      "name": "sched_change_group",
      "external": false,
      "loc": "kernel/sched/core.c:7011",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:sched_move_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718400,
      "name": "sched_change_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void sched_change_group(struct task_struct * tsk, int type)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void sched_change_group(struct task_struct * tsk, int type)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

# Function: <code>psi_task_change</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:510",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827177,
      "name": "psi_task_change.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071579825360,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:746",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858500,
      "name": "psi_task_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579854944,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:747",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907044,
      "name": "psi_task_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579903472,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579948784,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:767",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948784,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937248,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:783",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937248,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944368,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:788",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944368,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071376,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:800",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071376,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580204288,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:799",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:psi_memstall_leave",
        "kernel/sched/build_utility.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580204288,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580395488,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:885",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580395488,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580463936,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:908",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463936,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580523632,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:897",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:cgroup_move_task",
        "kernel/sched/build_utility.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523632,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491102896,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:747",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:dequeue_task",
        "kernel/sched/core.c:enqueue_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491102896,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225108700,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:747",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225108700,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283994128,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:747",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283994128,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1324
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271685864,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:747",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:move_queued_task",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271685864,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:747",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879156,
      "name": "psi_task_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579875584,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:747",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579814148,
      "name": "psi_task_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579810592,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:747",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867316,
      "name": "psi_task_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579863744,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
void psi_task_change(struct task_struct * task, int clear, int set)
```

```json
{
  "name": "psi_task_change",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_task_change",
      "external": true,
      "loc": "kernel/sched/psi.c:747",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:try_to_wake_up",
        "kernel/sched/core.c:deactivate_task",
        "kernel/sched/core.c:activate_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:cgroup_move_task",
        "kernel/sched/psi.c:psi_memstall_leave",
        "kernel/sched/psi.c:psi_memstall_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579912724,
      "name": "psi_task_change.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071579909136,
      "name": "psi_task_change",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 791
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
void psi_task_change(struct task_struct * task, int clear, int set)
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

# Function: <code>sched_move_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579567616,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7774",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_fork",
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/auto_group.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579567616,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578864,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7826",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/auto_group.c:autogroup_move_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578864,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579604960,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7979",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/auto_group.c:autogroup_move_group",
        "kernel/sched/auto_group.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604960,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583424,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:6193",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583424,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612784,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:6261",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612784,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579642656,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:6381",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642656,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680288,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:6362",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680288,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713216,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:6837",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713216,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1301
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755488,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7040",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755488,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789728,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7274",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789728,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579781280,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:8239",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579781280,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789408,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:8608",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789408,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884976,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:9846",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884976,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 635
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580002336,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:10169",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/build_utility.c:autogroup_move_group",
        "kernel/sched/build_utility.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002336,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 642
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164368,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:10349",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/build_utility.c:autogroup_move_group",
        "kernel/sched/build_utility.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164368,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580212704,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:10499",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/build_utility.c:autogroup_move_group",
        "kernel/sched/build_utility.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580212704,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 874
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580261360,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:10463",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/build_utility.c:autogroup_move_group",
        "kernel/sched/build_utility.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580261360,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 924
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490934128,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7040",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490934128,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224952360,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7040",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224952360,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1548
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283789648,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7040",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283789648,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1804
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271568058,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7040",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271568058,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579731408,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7040",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731408,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1541
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660256,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7040",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660256,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716992,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7040",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716992,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
void sched_move_task(struct task_struct * tsk)
```

```json
{
  "name": "sched_move_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763120,
      "name": "sched_move_task",
      "external": true,
      "loc": "kernel/sched/core.c:7040",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:cpu_cgroup_attach",
        "kernel/sched/autogroup.c:autogroup_move_group",
        "kernel/sched/autogroup.c:sched_autogroup_exit_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763120,
      "name": "sched_move_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1539
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

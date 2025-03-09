# Function: <code>move_queued_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct rq * move_queued_task(struct rq * rq, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546592,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1070",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__migrate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546592,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
struct rq * move_queued_task(struct rq * rq, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558016,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:988",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__migrate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558016,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
struct rq * move_queued_task(struct rq * rq, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579582960,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:995",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:__migrate_task"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579582960,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566400,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:916",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566400,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579596128,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:926",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596128,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579627776,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:931",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627776,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665296,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:926",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579665296,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579695632,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1369",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695632,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579736272,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1489",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736272,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1598
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579773712,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1554",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:migrate_tasks",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579773712,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761856,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1840",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761856,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769504,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1848",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769504,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:2226",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860160,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071592107382,
      "name": "move_queued_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:2325",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975552,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071593875123,
      "name": "move_queued_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:2321",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136112,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071595977509,
      "name": "move_queued_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:2496",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580214944,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071596495556,
      "name": "move_queued_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:2522",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__balance_push_cpu_stop",
        "kernel/sched/core.c:affine_move_task",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263680,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071597392444,
      "name": "move_queued_task.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490915840,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1489",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490915840,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224932460,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1489",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224932460,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1624
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283762640,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1489",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283762640,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1900
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271553214,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1489",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271553214,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579712896,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1489",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712896,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579640784,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1489",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640784,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1598
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579701248,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1489",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579701248,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
struct rq * move_queued_task(struct rq * rq, struct rq_flags * rf, struct task_struct * p, int new_cpu)
```

```json
{
  "name": "move_queued_task",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579743536,
      "name": "move_queued_task",
      "external": false,
      "loc": "kernel/sched/core.c:1489",
      "file": "kernel/sched/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_cpu_dying",
        "kernel/sched/core.c:__set_cpus_allowed_ptr",
        "kernel/sched/core.c:migration_cpu_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579743536,
      "name": "move_queued_task",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1598
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
<b>Param added. </b>
<code>struct rq_flags * rf</code>
</li>
<li>
<b>Param reordered. </b>
<code>rq, p, new_cpu</code> ➡️ <code>rq, rf, p, new_cpu</code>
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

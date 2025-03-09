# Function: <code>set_task_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579546384,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:929",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:sched_move_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579583702,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:929",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_move_group_fair",
        "kernel/sched/fair.c:task_fork_fair"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579570237,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:965",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579628232,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:965",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579595474,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:995",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579649860,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:995",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579579874,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1163",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579627060,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1163",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579609170,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1181",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579657748,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1181",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579638994,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1270",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690212,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1270",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579676674,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1424",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579728356,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1424",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579708565,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1482",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579758112,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1482",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579750661,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800856,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579786469,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1536",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579819466,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1536",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579777587,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1594",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579810794,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1594",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_task_rq(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579779536,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1605",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": [
        "kernel/sched/core.c:init_idle"
      ]
    },
    {
      "addr": 18446744071579817802,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1605",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224706,
      "name": "set_task_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_task_rq(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872992,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1893",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": [
        "kernel/sched/core.c:init_idle"
      ]
    },
    {
      "addr": 18446744071579919450,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1893",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592106432,
      "name": "set_task_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_task_rq(struct task_struct * p, unsigned int cpu)
```

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579988805,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1893",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": [
        "kernel/sched/core.c:init_idle"
      ]
    },
    {
      "addr": 18446744071580035865,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1893",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593874128,
      "name": "set_task_rq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580164914,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1942",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199269,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1942",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580213165,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1985",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272357,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1985",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580261864,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:2027",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_move_task",
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314037,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:2027",
      "file": "kernel/sched/fair.c",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490929128,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490980344,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224948876,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3224990112,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_change_group_fair",
        "kernel/sched/fair.c:task_change_group_fair"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283782356,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283847880,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271565774,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271594300,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579726613,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776704,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579655173,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579707336,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579713365,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761224,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/fair.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_task_rq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579758330,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:init_idle",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579809296,
      "name": "set_task_rq",
      "external": false,
      "loc": "kernel/sched/sched.h:1496",
      "file": "kernel/sched/fair.c",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void set_task_rq(struct task_struct * p, unsigned int cpu)
```
</details>
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
void set_task_rq(struct task_struct * p, unsigned int cpu)
```
</details>
</li>
</ul>

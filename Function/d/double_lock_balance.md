# Function: <code>double_lock_balance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int double_lock_balance(struct rq * this_rq, struct rq * busiest)
```

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579629308,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1568",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579637824,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1568",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:pull_dl_task"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637824,
      "name": "double_lock_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int double_lock_balance(struct rq * this_rq, struct rq * busiest)
```

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579643916,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1551",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579657532,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1551",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652720,
      "name": "double_lock_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668590,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1590",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579682078,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1590",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_timer"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int double_lock_balance(struct rq * this_rq, struct rq * busiest)
```

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579644221,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1823",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579655484,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1823",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653472,
      "name": "double_lock_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int double_lock_balance(struct rq * this_rq, struct rq * busiest)
```

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675375,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1862",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579686636,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1862",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq"
      ],
      "caller_func": [
        "kernel/sched/deadline.c:dl_task_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684000,
      "name": "double_lock_balance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579712971,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1906",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579721261,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1906",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579753067,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1941",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761917,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:1941",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579781740,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2003",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789109,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2003",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_timer",
        "kernel/sched/deadline.c:dl_task_timer"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579827260,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836354,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579866497,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2086",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:find_lock_lowest_rq",
        "kernel/sched/rt.c:find_lock_lowest_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882098,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2086",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579859070,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2209",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:find_lock_lowest_rq",
        "kernel/sched/rt.c:find_lock_lowest_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579875200,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2209",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579866651,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2245",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:find_lock_lowest_rq",
        "kernel/sched/rt.c:find_lock_lowest_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579884191,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2245",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579971046,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2580",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:find_lock_lowest_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579983701,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2580",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580089299,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2595",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:find_lock_lowest_rq"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580261529,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2653",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:find_lock_lowest_rq"
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
  "name": "double_lock_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580327593,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2699",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:find_lock_lowest_rq"
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
  "name": "double_lock_balance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580382537,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2755",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:pull_dl_task",
        "kernel/sched/build_policy.c:find_lock_later_rq",
        "kernel/sched/build_policy.c:dl_task_offline_migration",
        "kernel/sched/build_policy.c:pull_rt_task",
        "kernel/sched/build_policy.c:find_lock_lowest_rq"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491012172,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491023136,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225010952,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3225026144,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283875652,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283894644,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271618476,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271628288,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579800876,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579808706,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579734012,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743202,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579787628,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579796722,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "double_lock_balance",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579827774,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:pull_rt_task",
        "kernel/sched/rt.c:push_rt_task",
        "kernel/sched/rt.c:push_rt_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579838452,
      "name": "double_lock_balance",
      "external": false,
      "loc": "kernel/sched/sched.h:2046",
      "file": "kernel/sched/deadline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:pull_dl_task",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:find_lock_later_rq",
        "kernel/sched/deadline.c:dl_task_offline_migration",
        "kernel/sched/deadline.c:dl_task_offline_migration"
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

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int double_lock_balance(struct rq * this_rq, struct rq * busiest)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int double_lock_balance(struct rq * this_rq, struct rq * busiest)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int double_lock_balance(struct rq * this_rq, struct rq * busiest)
```
</details>
</li>
</ul>

# Function: <code>__cgroup_account_cputime</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112416,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/stat.c:226",
      "file": "kernel/cgroup/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112416,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580172368,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:362",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172368,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220256,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:362",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220256,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269152,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269152,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317312,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317312,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580389088,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:359",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580389088,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580376048,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:358",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580376048,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580378992,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:368",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580378992,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580540912,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:368",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580540912,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738304,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:373",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_utility.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738304,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014720,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:409",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_utility.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014720,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103136,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:393",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/build_policy.c:update_curr_dl",
        "kernel/sched/build_policy.c:update_curr_rt",
        "kernel/sched/build_utility.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103136,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200944,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:440",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/fair.c:update_curr_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200944,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491572440,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491572440,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225536012,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225536012,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284551408,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284551408,
      "name": "__cgroup_account_cputime",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271984082,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271984082,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580286112,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286112,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580233504,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233504,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580277360,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277360,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```

```json
{
  "name": "__cgroup_account_cputime",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580331200,
      "name": "__cgroup_account_cputime",
      "external": true,
      "loc": "kernel/cgroup/rstat.c:365",
      "file": "kernel/cgroup/rstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:update_curr",
        "kernel/sched/rt.c:update_curr_rt",
        "kernel/sched/deadline.c:update_curr_dl",
        "kernel/sched/stop_task.c:put_prev_task_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580331200,
      "name": "__cgroup_account_cputime",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void __cgroup_account_cputime(struct cgroup * cgrp, u64 delta_exec)
```
</details>
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

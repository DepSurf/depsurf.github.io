# Function: <code>security_task_setscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246640,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:972",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/cpuset.c:cpuset_can_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246640,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465280,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:996",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cpuset.c:cpuset_can_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465280,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557744,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1017",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557744,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582645120,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1660",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582645120,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799808,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1622",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799808,
      "name": "security_task_setscheduler",
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996432,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1126",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996432,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108608,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1734",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108608,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583294992,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1753",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294992,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400000,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400000,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739600,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1988",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739600,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859920,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:2005",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859920,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583886096,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:2068",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886096,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584249808,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:2076",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249808,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859760,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:2082",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859760,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585564368,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:2134",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564368,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585795360,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:3508",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_fork",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585795360,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043632,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:3567",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_fork",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043632,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495152632,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495152632,
      "name": "security_task_setscheduler",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228540228,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228540228,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289079200,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289079200,
      "name": "security_task_setscheduler",
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274399540,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274399540,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368736,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368736,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583305840,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305840,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583352512,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352512,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int security_task_setscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_setscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447696,
      "name": "security_task_setscheduler",
      "external": true,
      "loc": "security/security.c:1792",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_setaffinity",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/cgroup/cpuset.c:cpuset_can_attach",
        "fs/proc/base.c:timerslack_ns_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447696,
      "name": "security_task_setscheduler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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

# Function: <code>security_task_getscheduler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246720,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:977",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_getscheduler",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:SyS_sched_rr_get_interval"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246720,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465360,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1001",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getscheduler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465360,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557824,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1022",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557824,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582645200,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1665",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:SyS_sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582645200,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799888,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1627",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:SyS_sched_getattr",
        "kernel/sched/core.c:SyS_sched_getparam",
        "kernel/sched/core.c:SyS_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799888,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996496,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1131",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996496,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108672,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1739",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108672,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583295072,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1758",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583295072,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400064,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400064,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739664,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1993",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739664,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859984,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:2010",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859984,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583886160,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:2073",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886160,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584249872,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:2081",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249872,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859840,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:2087",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859840,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585564464,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:2139",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564464,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585795456,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:3521",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585795456,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043728,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:3580",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043728,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495152712,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__arm64_sys_sched_getattr",
        "kernel/sched/core.c:__arm64_sys_sched_getparam",
        "kernel/sched/core.c:__arm64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495152712,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228540312,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__se_sys_sched_getattr",
        "kernel/sched/core.c:__se_sys_sched_getparam",
        "kernel/sched/core.c:__se_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228540312,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289079376,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__se_sys_sched_getattr",
        "kernel/sched/core.c:__se_sys_sched_getparam",
        "kernel/sched/core.c:__se_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289079376,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274399600,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__se_sys_sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__se_sys_sched_getattr",
        "kernel/sched/core.c:__se_sys_sched_getparam",
        "kernel/sched/core.c:__se_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274399600,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368800,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368800,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583305904,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305904,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583352576,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352576,
      "name": "security_task_getscheduler",
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
int security_task_getscheduler(struct task_struct * p)
```

```json
{
  "name": "security_task_getscheduler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447760,
      "name": "security_task_getscheduler",
      "external": true,
      "loc": "security/security.c:1797",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_rr_get_interval",
        "kernel/sched/core.c:sched_getaffinity",
        "kernel/sched/core.c:__ia32_sys_sched_getattr",
        "kernel/sched/core.c:__x64_sys_sched_getattr",
        "kernel/sched/core.c:__ia32_sys_sched_getparam",
        "kernel/sched/core.c:__x64_sys_sched_getparam",
        "kernel/sched/core.c:__ia32_sys_sched_getscheduler",
        "kernel/sched/core.c:__x64_sys_sched_getscheduler",
        "fs/proc/base.c:timerslack_ns_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447760,
      "name": "security_task_getscheduler",
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

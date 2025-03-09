# Function: <code>security_task_setnice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582246304,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:951",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582246304,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582464944,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:975",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582464944,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582557408,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:996",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/auto_group.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557408,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582644688,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1633",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582644688,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582799312,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1595",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:SyS_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582799312,
      "name": "security_task_setnice",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582996048,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1099",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996048,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583108224,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1707",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583108224,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583294560,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1726",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294560,
      "name": "security_task_setnice",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583399616,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1765",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583399616,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739216,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1961",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739216,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859536,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1978",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859536,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583885712,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:2041",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583885712,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584249424,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:2049",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584249424,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859264,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:2055",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859264,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585563792,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:2107",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563792,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585794784,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:3432",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585794784,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043056,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:3491",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/build_utility.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043056,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495152152,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1765",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__arm64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495152152,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228539760,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1765",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__se_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228539760,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289078224,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1765",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__se_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289078224,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274399192,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1765",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274399192,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583368352,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1765",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368352,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583305456,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1765",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583305456,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583352128,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1765",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352128,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int security_task_setnice(struct task_struct * p, int nice)
```

```json
{
  "name": "security_task_setnice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447312,
      "name": "security_task_setnice",
      "external": true,
      "loc": "security/security.c:1765",
      "file": "security/security.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:set_one_prio",
        "kernel/sched/core.c:__ia32_sys_nice",
        "kernel/sched/core.c:__x64_sys_nice",
        "kernel/sched/autogroup.c:proc_sched_autogroup_set_nice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447312,
      "name": "security_task_setnice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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

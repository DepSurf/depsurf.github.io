# Function: <code>find_get_task_by_vpid</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570288,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:346",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570288,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607472,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:355",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607472,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631808,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631808,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579657360,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579657360,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579689808,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:424",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/taskstats.c:fill_stats_for_pid",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689808,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667984,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/taskstats.c:fill_stats_for_pid",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667984,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674800,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/taskstats.c:cmd_attr_pid",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674800,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752448,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x64_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/taskstats.c:cmd_attr_pid",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752448,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857248,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/taskstats.c:cmd_attr_pid",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857248,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998416,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:425",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/taskstats.c:cmd_attr_pid",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998416,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580052912,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:428",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/taskstats.c:cmd_attr_pid",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580052912,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095376,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:428",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex/pi.c:futex_lock_pi_atomic",
        "kernel/taskstats.c:cmd_attr_pid",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095376,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490831080,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__arm64_compat_sys_ptrace",
        "kernel/ptrace.c:__arm64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/taskstats.c:taskstats_user_cmd",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490831080,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224861824,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/taskstats.c:taskstats_user_cmd",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224861824,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283665680,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_compat_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/taskstats.c:taskstats_user_cmd",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283665680,
      "name": "find_get_task_by_vpid",
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271502448,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/taskstats.c:taskstats_user_cmd",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271502448,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633680,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633680,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562000,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562000,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579630944,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630944,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct task_struct * find_get_task_by_vpid(pid_t nr)
```

```json
{
  "name": "find_get_task_by_vpid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664752,
      "name": "find_get_task_by_vpid",
      "external": true,
      "loc": "kernel/pid.c:358",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__x32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_compat_sys_ptrace",
        "kernel/ptrace.c:__ia32_sys_ptrace",
        "kernel/ptrace.c:__x64_sys_ptrace",
        "kernel/futex.c:attach_to_pi_owner",
        "security/yama/yama_lsm.c:yama_task_prctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664752,
      "name": "find_get_task_by_vpid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct task_struct * find_get_task_by_vpid(pid_t nr)
```
</details>
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

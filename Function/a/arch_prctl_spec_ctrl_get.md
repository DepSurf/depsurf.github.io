# Function: <code>arch_prctl_spec_ctrl_get</code>

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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579122016,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:625",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579122016,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579128304,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:921",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579128304,
      "name": "arch_prctl_spec_ctrl_get",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139280,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1131",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139280,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141408,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1261",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141408,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579156816,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1378",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156816,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579154032,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1386",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579154032,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579161376,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1386",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161376,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191888,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1539",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191888,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240336,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2041",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240336,
      "name": "arch_prctl_spec_ctrl_get",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299840,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2092",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299840,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579306192,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2203",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306192,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579337136,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:2345",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__do_sys_prctl",
        "fs/proc/array.c:task_seccomp",
        "fs/proc/array.c:task_seccomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337136,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490336552,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/arm64/kernel/ssbd.c:121",
      "file": "arch/arm64/kernel/ssbd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490336552,
      "name": "arch_prctl_spec_ctrl_get",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int arch_prctl_spec_ctrl_get(struct task_struct * t, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224822536,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "kernel/sys.c:2266",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224822536,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
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
int arch_prctl_spec_ctrl_get(struct task_struct * t, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283611360,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "kernel/sys.c:2266",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283611360,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 16
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
int arch_prctl_spec_ctrl_get(struct task_struct * t, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271468964,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "kernel/sys.c:2266",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271468964,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141776,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1261",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141776,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073008,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1261",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073008,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141328,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1261",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141328,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
```

```json
{
  "name": "arch_prctl_spec_ctrl_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579146464,
      "name": "arch_prctl_spec_ctrl_get",
      "external": true,
      "loc": "arch/x86/kernel/cpu/bugs.c:1261",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "fs/proc/array.c:proc_pid_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146464,
      "name": "arch_prctl_spec_ctrl_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int arch_prctl_spec_ctrl_get(struct task_struct * task, long unsigned int which)
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct * t</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
</details>
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

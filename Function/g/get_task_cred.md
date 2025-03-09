# Function: <code>get_task_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579510112,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:187",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cgroup.c:__cgroup_procs_write",
        "fs/proc/array.c:proc_pid_status",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510112,
      "name": "get_task_cred",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524256,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:187",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:proc_pid_status",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524256,
      "name": "get_task_cred",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547904,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:187",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:proc_pid_status",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547904,
      "name": "get_task_cred",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579534592,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:188",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cgroup/cgroup.c:__cgroup_procs_write",
        "fs/proc/array.c:proc_pid_status",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534592,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579561120,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:188",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:proc_pid_status",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561120,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579589136,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:188",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:proc_pid_status",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589136,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579625552,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:189",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:proc_pid_status",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_pid",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625552,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579650128,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650128,
      "name": "get_task_cred",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579687168,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687168,
      "name": "get_task_cred",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579727200,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727200,
      "name": "get_task_cred",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579705888,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579705888,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579713024,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:196",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713024,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579791056,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:196",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791056,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579898224,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:196",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898224,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050048,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:196",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/domain.c:may_change_ptraced_domain",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050048,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580104496,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:196",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/domain.c:may_change_ptraced_domain",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580104496,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149408,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:153",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/domain.c:may_change_ptraced_domain",
        "security/apparmor/lsm.c:apparmor_task_kill",
        "security/apparmor/lsm.c:apparmor_getprocattr",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149408,
      "name": "get_task_cred",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490863504,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490863504,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224882964,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224882964,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283694160,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283694160,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271521594,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271521594,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579663488,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663488,
      "name": "get_task_cred",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579591840,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591840,
      "name": "get_task_cred",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579660752,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660752,
      "name": "get_task_cred",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
const struct cred * get_task_cred(struct task_struct * task)
```

```json
{
  "name": "get_task_cred",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579694848,
      "name": "get_task_cred",
      "external": true,
      "loc": "kernel/cred.c:193",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write",
        "kernel/cred.c:prepare_kernel_cred",
        "fs/proc/array.c:task_state",
        "security/apparmor/lsm.c:apparmor_getprocattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694848,
      "name": "get_task_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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

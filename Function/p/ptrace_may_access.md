# Function: <code>ptrace_may_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416848,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:307",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/events/core.c:SYSC_perf_event_open",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416848,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429136,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:306",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/events/core.c:SYSC_perf_event_open",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:timerslack_ns_show",
        "fs/proc/base.c:timerslack_ns_write",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429136,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579449504,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:319",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/events/core.c:SYSC_perf_event_open",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449504,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579437456,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:334",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/migrate.c:SYSC_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579437456,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465728,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:334",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/kcmp.c:SyS_kcmp",
        "kernel/futex.c:SyS_get_robust_list",
        "kernel/futex_compat.c:compat_SyS_get_robust_list",
        "kernel/events/core.c:SYSC_perf_event_open",
        "mm/mempolicy.c:SYSC_migrate_pages",
        "mm/migrate.c:SYSC_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465728,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480336,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:334",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/futex_compat.c:__x32_compat_sys_get_robust_list",
        "kernel/futex_compat.c:__ia32_compat_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480336,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513680,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:334",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__ia32_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/kcmp.c:__x64_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513680,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533344,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:349",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533344,
      "name": "ptrace_may_access",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559488,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559488,
      "name": "ptrace_may_access",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591136,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_stack",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591136,
      "name": "ptrace_may_access",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571152,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:348",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_stack",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571152,
      "name": "ptrace_may_access",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579576720,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:365",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_stack",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576720,
      "name": "ptrace_may_access",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650864,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:365",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/sched/core_sched.c:sched_core_share_pid",
        "kernel/sched/core_sched.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x64_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_stack",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/fd.c:seq_fdinfo_open",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650864,
      "name": "ptrace_may_access",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746080,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:359",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex/syscalls.c:__ia32_sys_get_robust_list",
        "kernel/futex/syscalls.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_syscall",
        "fs/proc/base.c:proc_pid_stack",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746080,
      "name": "ptrace_may_access",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579877456,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:359",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex/syscalls.c:__ia32_sys_get_robust_list",
        "kernel/futex/syscalls.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_syscall",
        "fs/proc/base.c:proc_pid_stack",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579877456,
      "name": "ptrace_may_access",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926768,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:360",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex/syscalls.c:__ia32_sys_get_robust_list",
        "kernel/futex/syscalls.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_syscall",
        "fs/proc/base.c:proc_pid_stack",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926768,
      "name": "ptrace_may_access",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966080,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:349",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/pid.c:pidfd_getfd",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex/syscalls.c:__ia32_sys_get_robust_list",
        "kernel/futex/syscalls.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:find_mm_struct",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:proc_pid_lookup",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_readlink",
        "fs/proc/base.c:proc_pid_get_link",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_pid_syscall",
        "fs/proc/base.c:proc_pid_stack",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/fd.c:proc_open_fdinfo",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966080,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490714752,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/kcmp.c:__arm64_sys_kcmp",
        "kernel/futex.c:__arm64_compat_sys_get_robust_list",
        "kernel/futex.c:__arm64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490714752,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224772600,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/futex.c:__se_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224772600,
      "name": "ptrace_may_access",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283539120,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/futex.c:__se_compat_sys_get_robust_list",
        "kernel/futex.c:__se_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283539120,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271433674,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/futex.c:__se_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271433674,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535792,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535792,
      "name": "ptrace_may_access",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464576,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464576,
      "name": "ptrace_may_access",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533072,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533072,
      "name": "ptrace_may_access",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool ptrace_may_access(struct task_struct * task, unsigned int mode)
```

```json
{
  "name": "ptrace_may_access",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566144,
      "name": "ptrace_may_access",
      "external": true,
      "loc": "kernel/ptrace.c:354",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:mm_access",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/futex.c:__x32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_compat_sys_get_robust_list",
        "kernel/futex.c:__ia32_sys_get_robust_list",
        "kernel/futex.c:__x64_sys_get_robust_list",
        "kernel/events/core.c:__do_sys_perf_event_open",
        "mm/mempolicy.c:kernel_migrate_pages",
        "mm/migrate.c:kernel_move_pages",
        "fs/proc/base.c:proc_pid_readdir",
        "fs/proc/base.c:do_io_accounting",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:pid_getattr",
        "fs/proc/base.c:proc_pid_permission",
        "fs/proc/base.c:proc_fd_access_allowed",
        "fs/proc/base.c:proc_pid_wchan",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/namespaces.c:proc_ns_readlink",
        "fs/proc/namespaces.c:proc_ns_get_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566144,
      "name": "ptrace_may_access",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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

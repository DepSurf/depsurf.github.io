# Function: <code>check_zeroed_user</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584268704,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:50",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/events/core.c:perf_copy_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268704,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584676464,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:51",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/events/core.c:perf_copy_attr",
        "fs/open.c:__ia32_sys_openat2",
        "fs/open.c:__x64_sys_openat2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676464,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584794016,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:54",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/events/core.c:perf_copy_attr",
        "fs/open.c:__ia32_sys_openat2",
        "fs/open.c:__x64_sys_openat2",
        "fs/io_uring.c:io_req_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584794016,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584838256,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:54",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/events/core.c:perf_copy_attr",
        "fs/open.c:__ia32_sys_openat2",
        "fs/open.c:__x64_sys_openat2",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/io_uring.c:io_req_prep",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584838256,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585257632,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:54",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/events/core.c:perf_copy_attr",
        "fs/open.c:__ia32_sys_openat2",
        "fs/open.c:__x64_sys_openat2",
        "fs/namespace.c:__do_sys_mount_setattr",
        "fs/io_uring.c:io_req_prep",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257632,
      "name": "check_zeroed_user",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586100224,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:54",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/events/core.c:perf_copy_attr",
        "fs/open.c:__do_sys_openat2",
        "fs/namespace.c:__do_sys_mount_setattr",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset",
        "io_uring/io_uring.c:io_openat2_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586100224,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587085008,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:62",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/events/core.c:perf_copy_attr",
        "fs/open.c:__do_sys_openat2",
        "fs/namespace.c:__do_sys_mount_setattr",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset",
        "io_uring/openclose.c:io_openat2_prep",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587085008,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587344000,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:62",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/trace/trace_events_user.c:user_events_ioctl_unreg",
        "kernel/trace/trace_events_user.c:user_events_ioctl_reg",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/events/core.c:perf_copy_attr",
        "fs/open.c:__ia32_sys_openat2",
        "fs/open.c:__x64_sys_openat2",
        "fs/namespace.c:__ia32_sys_mount_setattr",
        "fs/namespace.c:__x64_sys_mount_setattr",
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset",
        "io_uring/openclose.c:io_openat2_prep",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587344000,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587627472,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:62",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_addfd",
        "kernel/seccomp.c:seccomp_notify_recv",
        "kernel/trace/trace_events_user.c:user_events_ioctl_unreg",
        "kernel/trace/trace_events_user.c:user_events_ioctl_reg",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/events/core.c:perf_copy_attr",
        "fs/open.c:__ia32_sys_openat2",
        "fs/open.c:__x64_sys_openat2",
        "fs/namespace.c:copy_mnt_id_req",
        "fs/namespace.c:__ia32_sys_mount_setattr",
        "fs/namespace.c:__x64_sys_mount_setattr",
        "security/landlock/syscalls.c:__do_sys_landlock_create_ruleset",
        "io_uring/openclose.c:io_openat2_prep",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587627472,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496152080,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:50",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:__arm64_sys_sched_setattr",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/events/core.c:perf_copy_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496152080,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229473124,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:50",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/events/core.c:perf_copy_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229473124,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290413056,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:50",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/events/core.c:perf_copy_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290413056,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275205748,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:50",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:__se_sys_sched_setattr",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/events/core.c:perf_copy_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275205748,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237440,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:50",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/events/core.c:perf_copy_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237440,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172640,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:50",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/events/core.c:perf_copy_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172640,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584221200,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:50",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/events/core.c:perf_copy_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584221200,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int check_zeroed_user(const void * from, size_t size)
```

```json
{
  "name": "check_zeroed_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584326032,
      "name": "check_zeroed_user",
      "external": true,
      "loc": "lib/usercopy.c:50",
      "file": "lib/usercopy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_clone_args_from_user",
        "kernel/sched/core.c:sched_copy_attr",
        "kernel/seccomp.c:seccomp_notify_ioctl",
        "kernel/events/core.c:perf_copy_attr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584326032,
      "name": "check_zeroed_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int check_zeroed_user(const void * from, size_t size)
```
</details>
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

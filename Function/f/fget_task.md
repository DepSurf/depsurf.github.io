# Function: <code>fget_task</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct file * fget_task(struct task_struct * task, unsigned int fd)
```

```json
{
  "name": "fget_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582226736,
      "name": "fget_task",
      "external": true,
      "loc": "fs/file.c:763",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_getfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226736,
      "name": "fget_task",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct file * fget_task(struct task_struct * task, unsigned int fd)
```

```json
{
  "name": "fget_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582274912,
      "name": "fget_task",
      "external": true,
      "loc": "fs/file.c:863",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:kcmp_epoll_target",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/proc/fd.c:proc_fd_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582274912,
      "name": "fget_task",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct file * fget_task(struct task_struct * task, unsigned int fd)
```

```json
{
  "name": "fget_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582300416,
      "name": "fget_task",
      "external": true,
      "loc": "fs/file.c:875",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/proc/fd.c:proc_fd_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300416,
      "name": "fget_task",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct file * fget_task(struct task_struct * task, unsigned int fd)
```

```json
{
  "name": "fget_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582619456,
      "name": "fget_task",
      "external": true,
      "loc": "fs/file.c:935",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/proc/fd.c:proc_fd_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619456,
      "name": "fget_task",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct file * fget_task(struct task_struct * task, unsigned int fd)
```

```json
{
  "name": "fget_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154336,
      "name": "fget_task",
      "external": true,
      "loc": "fs/file.c:937",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/proc/fd.c:proc_fd_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154336,
      "name": "fget_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct file * fget_task(struct task_struct * task, unsigned int fd)
```

```json
{
  "name": "fget_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728112,
      "name": "fget_task",
      "external": true,
      "loc": "fs/file.c:937",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/proc/fd.c:proc_fd_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728112,
      "name": "fget_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct file * fget_task(struct task_struct * task, unsigned int fd)
```

```json
{
  "name": "fget_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945168,
      "name": "fget_task",
      "external": true,
      "loc": "fs/file.c:938",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/proc/fd.c:proc_fd_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945168,
      "name": "fget_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct file * fget_task(struct task_struct * task, unsigned int fd)
```

```json
{
  "name": "fget_task",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584152336,
      "name": "fget_task",
      "external": true,
      "loc": "fs/file.c:1060",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:pidfd_getfd",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/proc/fd.c:proc_fd_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584152336,
      "name": "fget_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct file * fget_task(struct task_struct * task, unsigned int fd)
```
</details>
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

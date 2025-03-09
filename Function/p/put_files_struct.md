# Function: <code>put_files_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581115760,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:430",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "fs/file.c:reset_files_struct",
        "fs/file.c:exit_files",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:seq_show",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581115760,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581281472,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:431",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281472,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581359920,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:431",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359920,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581415184,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:417",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/kcmp.c:SyS_kcmp",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415184,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581556800,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:418",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:SyS_unshare",
        "kernel/kcmp.c:SyS_kcmp",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:tid_fd_revalidate",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556800,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581713664,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:kcmp_epoll_target",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713664,
      "name": "put_files_struct",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581800384,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:kcmp_epoll_target",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800384,
      "name": "put_files_struct",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581919168,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581919168,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581991552,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991552,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582225392,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:kcmp_epoll_target",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "fs/exec.c:__do_execve_file",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582225392,
      "name": "put_files_struct",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582273616,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:415",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range",
        "fs/file.c:exit_files",
        "fs/io_uring.c:io_req_clean_work",
        "fs/io_uring.c:io_sq_thread_drop_mm_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582273616,
      "name": "put_files_struct",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582299088,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:415",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range",
        "fs/file.c:exit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582299088,
      "name": "put_files_struct",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582618160,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:415",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range",
        "fs/file.c:exit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582618160,
      "name": "put_files_struct",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583153008,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:444",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range",
        "fs/file.c:exit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153008,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583726784,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:444",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range",
        "fs/file.c:exit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726784,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583943840,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:444",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range",
        "fs/file.c:exit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583943840,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584150624,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:444",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:unshare_files",
        "kernel/fork.c:ksys_unshare",
        "fs/file.c:__close_range",
        "fs/file.c:exit_files"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150624,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493505968,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:kcmp_epoll_target",
        "kernel/kcmp.c:kcmp_epoll_target",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493505968,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227062952,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "fs/exec.c:__do_execve_file",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227062952,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287069376,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287069376,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273178782,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct"
      ],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:__se_sys_kcmp",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/exec.c:__do_execve_file",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273175078,
      "name": "put_files_struct.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    },
    {
      "addr": 18446743936273178450,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581960288,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581960288,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581897856,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581897856,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581951600,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951600,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void put_files_struct(struct files_struct * files)
```

```json
{
  "name": "put_files_struct",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582021792,
      "name": "put_files_struct",
      "external": true,
      "loc": "fs/file.c:413",
      "file": "fs/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:ksys_unshare",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/kcmp.c:__do_sys_kcmp",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "fs/file.c:exit_files",
        "fs/file.c:reset_files_struct",
        "fs/coredump.c:do_coredump",
        "fs/proc/fd.c:proc_readfd_common",
        "fs/proc/fd.c:proc_fd_link",
        "fs/proc/fd.c:tid_fd_mode",
        "fs/proc/fd.c:seq_show",
        "fs/proc/fd.c:seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582021792,
      "name": "put_files_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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

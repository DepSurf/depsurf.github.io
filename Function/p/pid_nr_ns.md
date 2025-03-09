# Function: <code>pid_nr_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491408,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:500",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:task_tgid_nr_ns",
        "kernel/pid.c:__task_pid_nr_ns"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "fs/proc/base.c:show_timer",
        "fs/proc/base.c:next_tgid",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/fuse/file.c:fuse_setlk",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491408,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579505511,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:500",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:task_tgid_nr_ns",
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/fuse/file.c:fuse_setlk",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505328,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579526183,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:500",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:task_tgid_nr_ns",
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/fuse/file.c:fuse_setlk",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526000,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513939,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:501",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/fuse/file.c:fuse_setlk",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513680,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579540707,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:370",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540336,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568211,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:395",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/fuse/dev.c:fuse_get_req_nofail_nopages",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568000,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579605400,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:402",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:proc_pid_status",
        "fs/fuse/dev.c:fuse_get_req_nofail_nopages",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605184,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579629471,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_get_req_nofail_nopages",
        "fs/fuse/dev.c:__fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629072,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579654992,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654624,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579685836,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:471",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685648,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664238,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:472",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_show_fdinfo",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663904,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671054,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:472",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_show_fdinfo",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670720,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579748724,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:472",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_show_fdinfo",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748384,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579853162,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:472",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_show_fdinfo",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852736,
      "name": "pid_nr_ns",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579993882,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:472",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_show_fdinfo",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993376,
      "name": "pid_nr_ns",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580047706,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:475",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_show_fdinfo",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047200,
      "name": "pid_nr_ns",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090202,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:475",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_show_fdinfo",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/bpf/task_iter.c:task_seq_get_next",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089696,
      "name": "pid_nr_ns",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490827880,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490827528,
      "name": "pid_nr_ns",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224859572,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859272,
      "name": "pid_nr_ns",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283662264,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283661760,
      "name": "pid_nr_ns",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271500204,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271499778,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579631312,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579630944,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579559648,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559280,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628576,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628208,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
pid_t pid_nr_ns(struct pid * pid, struct pid_namespace * ns)
```

```json
{
  "name": "pid_nr_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662482,
      "name": "pid_nr_ns",
      "external": true,
      "loc": "kernel/pid.c:405",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_show_fdinfo",
        "fs/proc/base.c:next_tgid",
        "fs/proc/base.c:show_timer",
        "fs/proc/array.c:children_seq_show",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:task_state",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/file.c:fuse_setlk",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/msg.c:sysvipc_msg_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "ipc/shm.c:sysvipc_shm_proc_show",
        "net/ipv6/ip6_flowlabel.c:ip6fl_seq_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661792,
      "name": "pid_nr_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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

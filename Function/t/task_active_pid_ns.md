# Function: <code>task_active_pid_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491119,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:545",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/sysctl_binary.c:do_sysctl",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:acct_process",
        "kernel/cgroup.c:cgroup_pidlist_find",
        "kernel/cgroup.c:pidlist_array_load",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/events/core.c:perf_event_alloc",
        "fs/proc/root.c:proc_mount",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/inode.c:fuse_conn_init",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491648,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579505721,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:545",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/sysctl_binary.c:do_sysctl",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/proc/root.c:proc_mount",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/inode.c:fuse_conn_init",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505568,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579526393,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:545",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/sysctl_binary.c:do_sysctl",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/cgroup.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/proc/root.c:proc_mount",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/dev.c:fuse_dev_do_write",
        "fs/fuse/inode.c:fuse_conn_init",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526240,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513979,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:543",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "fs/proc/root.c:proc_mount",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513824,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579540745,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:413",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:SyS_acct",
        "kernel/acct.c:SyS_acct",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_mount",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540480,
      "name": "task_active_pid_ns",
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579568248,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:438",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_mount",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568384,
      "name": "task_active_pid_ns",
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579605418,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:438",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_mount",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605472,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579629490,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629232,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579655044,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654784,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579685898,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:506",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:find_child_reaper",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/taskstats.c:fill_stats_for_pid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:init_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "fs/exec.c:exec_binprm",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685936,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664309,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:507",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:find_child_reaper",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find_create",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/taskstats.c:fill_stats_for_pid",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:init_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "fs/exec.c:exec_binprm",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664064,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579671125,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:507",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:forget_original_parent",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:init_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "fs/exec.c:exec_binprm",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670880,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579748802,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:507",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:forget_original_parent",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:init_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "fs/exec.c:exec_binprm",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748544,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858264,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:507",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:forget_original_parent",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:init_seq_pidns",
        "kernel/events/core.c:perf_event_alloc",
        "fs/exec.c:exec_binprm",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852928,
      "name": "task_active_pid_ns",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999448,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:507",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:forget_original_parent",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:init_seq_pidns",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/events/core.c:perf_event_alloc",
        "fs/exec.c:exec_binprm",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993600,
      "name": "task_active_pid_ns",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048873,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:510",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:forget_original_parent",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:add_del_listener",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:init_seq_pidns",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/exec.c:exec_binprm",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047424,
      "name": "task_active_pid_ns",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091369,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:510",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:forget_original_parent",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/nsproxy.c:validate_nsset",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:pid_mfd_noexec_dointvec_minmax",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:add_del_listener",
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_fill_link_info",
        "kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid",
        "kernel/bpf/task_iter.c:init_seq_pidns",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memfd.c:__do_sys_memfd_create",
        "fs/exec.c:exec_binprm",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089920,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490827952,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__arm64_sys_acct",
        "kernel/acct.c:__arm64_sys_acct",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490827752,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224859628,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/pid.c:find_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/exec.c:__do_execve_file",
        "fs/locks.c:fcntl_getlk64",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859460,
      "name": "task_active_pid_ns",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283662340,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:add_del_listener",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283661952,
      "name": "task_active_pid_ns",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271500250,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__se_sys_acct",
        "kernel/acct.c:__se_sys_acct",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:add_del_listener",
        "fs/exec.c:__do_execve_file",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271499944,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579631364,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631104,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579559700,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559440,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628628,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628368,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
struct pid_namespace * task_active_pid_ns(struct task_struct * tsk)
```

```json
{
  "name": "task_active_pid_ns",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579662546,
      "name": "task_active_pid_ns",
      "external": true,
      "loc": "kernel/pid.c:441",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__task_pid_nr_ns",
        "kernel/pid.c:pid_vnr",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:do_exit",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/acct.c:acct_process",
        "kernel/acct.c:__ia32_sys_acct",
        "kernel/acct.c:__x64_sys_acct",
        "kernel/acct.c:acct_on",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_find",
        "kernel/pid_namespace.c:pidns_get_parent",
        "kernel/pid_namespace.c:pidns_install",
        "kernel/pid_namespace.c:pidns_get",
        "kernel/pid_namespace.c:pid_ns_ctl_handler",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/audit.c:audit_receive_msg",
        "kernel/taskstats.c:add_del_listener",
        "kernel/events/core.c:perf_event_alloc",
        "fs/locks.c:fcntl_getlk",
        "fs/proc/root.c:proc_init_fs_context",
        "fs/proc/loadavg.c:loadavg_proc_show",
        "fs/fuse/inode.c:fuse_conn_init",
        "ipc/util.c:sysvipc_proc_open",
        "net/core/scm.c:__scm_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661952,
      "name": "task_active_pid_ns",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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

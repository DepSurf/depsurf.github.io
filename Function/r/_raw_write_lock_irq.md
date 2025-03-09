# Function: <code>_raw_write_lock_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587381584,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:release_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_request",
        "kernel/sys.c:SyS_setpgid",
        "kernel/sys.c:sys_setsid",
        "fs/fcntl.c:f_modown",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_load_policy",
        "security/selinux/ss/services.c:security_set_bools",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381584,
      "name": "_raw_write_lock_irq",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587884544,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid",
        "fs/fcntl.c:f_modown",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884544,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588102848,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid",
        "fs/fcntl.c:f_modown",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588102848,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328496,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid",
        "fs/fcntl.c:f_modown",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328496,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588894928,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:302",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_setpgid",
        "fs/fcntl.c:f_delown",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894928,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589273152,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:302",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589273152,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589516224,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:302",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589516224,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589975328,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589975328,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590202624,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590202624,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591218432,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:find_child_reaper",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:unshare_sighand",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "net/netlink/af_netlink.c:netlink_change_ngroups",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591218432,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591712864,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:find_child_reaper",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:unshare_sighand",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_modify",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "net/netlink/af_netlink.c:netlink_change_ngroups",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591712864,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591660320,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "net/netlink/af_netlink.c:netlink_change_ngroups",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591660320,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592834048,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:314",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "net/netlink/af_netlink.c:netlink_change_ngroups",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592834048,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594745872,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:324",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "net/netlink/af_netlink.c:netlink_change_ngroups",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594745872,
      "name": "_raw_write_lock_irq",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596498992,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:324",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:unshare_sighand",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_change_ngroups",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596498992,
      "name": "_raw_write_lock_irq",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597036560,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:324",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:unshare_sighand",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:__ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_change_ngroups",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597036560,
      "name": "_raw_write_lock_irq",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597968528,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:324",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:unshare_sighand",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:__ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_change_ngroups",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597968528,
      "name": "_raw_write_lock_irq",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236558076,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:ptrace_request",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__do_sys_epoll_ctl",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236558076,
      "name": "_raw_write_lock_irq",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297805120,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297805120,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279811166,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:__se_sys_ptrace",
        "kernel/ptrace.c:ptrace_request",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:do_epoll_wait",
        "fs/eventpoll.c:__se_sys_epoll_ctl",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279811166,
      "name": "_raw_write_lock_irq",
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589804912,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589804912,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589527264,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589527264,
      "name": "_raw_write_lock_irq",
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590248320,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590248320,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void _raw_write_lock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_lock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590300000,
      "name": "_raw_write_lock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:309",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590300000,
      "name": "_raw_write_lock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void _raw_write_lock_irq(rwlock_t * lock)
```
</details>
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

# Function: <code>_raw_write_unlock_irq</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594745024,
      "name": "_raw_write_unlock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:356",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
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
      "addr": 18446744071594745024,
      "name": "_raw_write_unlock_irq",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596497872,
      "name": "_raw_write_unlock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:356",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:unshare_sighand",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
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
      "addr": 18446744071596497872,
      "name": "_raw_write_unlock_irq",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597035440,
      "name": "_raw_write_unlock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:356",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:unshare_sighand",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:__ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "net/netlink/af_netlink.c:netlink_proto_init",
        "net/netlink/af_netlink.c:netlink_change_ngroups",
        "net/netlink/af_netlink.c:__netlink_kernel_create",
        "net/netlink/af_netlink.c:netlink_setsockopt",
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
      "addr": 18446744071597035440,
      "name": "_raw_write_unlock_irq",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597967408,
      "name": "_raw_write_unlock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:356",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:exit_notify",
        "kernel/exit.c:forget_original_parent",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__do_sys_setpgid",
        "fs/exec.c:unshare_sighand",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_delown",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:do_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_send_events",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:ep_insert",
        "fs/eventpoll.c:__ep_remove",
        "fs/eventpoll.c:ep_done_scan",
        "fs/kernfs/dir.c:kernfs_rename_ns",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "drivers/scsi/sg.c:sg_ioctl_common",
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
      "addr": 18446744071597967408,
      "name": "_raw_write_unlock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void _raw_write_unlock_irq(rwlock_t * lock)
```

```json
{
  "name": "_raw_write_unlock_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590299184,
      "name": "_raw_write_unlock_irq",
      "external": true,
      "loc": "kernel/locking/spinlock.c:341",
      "file": "kernel/locking/spinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_traceme",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/ptrace.c:ptrace_attach",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_setpgid",
        "kernel/sys.c:__x64_sys_setpgid",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/exec.c:de_thread",
        "fs/fcntl.c:fasync_insert_entry",
        "fs/fcntl.c:fasync_remove_entry",
        "fs/fcntl.c:f_modown",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__ia32_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:__x64_sys_epoll_ctl",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_poll",
        "fs/eventpoll.c:ep_remove",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/keys/keyctl.c:keyctl_session_to_parent",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_set_bools",
        "security/selinux/ss/services.c:security_load_policy",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/scsi/sg.c:sg_ioctl",
        "net/netlink/af_netlink.c:netlink_table_ungrab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299184,
      "name": "_raw_write_unlock_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void _raw_write_unlock_irq(rwlock_t * lock)
```
</details>
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ➕</summary>

```c
void _raw_write_unlock_irq(rwlock_t * lock)
```
</details>
</li>
</ul>

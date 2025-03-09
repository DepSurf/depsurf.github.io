# Function: <code>pid_vnr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491472,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:514",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:SYSC_kill",
        "kernel/sys.c:sys_getpid",
        "kernel/sys.c:sys_getppid",
        "kernel/sys.c:sys_getpgrp",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:sys_setsid",
        "kernel/cgroup.c:pidlist_array_load",
        "kernel/audit.c:audit_receive_msg",
        "kernel/trace/ftrace.c:fpid_show",
        "fs/fcntl.c:f_getown",
        "fs/fcntl.c:SyS_fcntl",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:posix_test_lock",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgrcv",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:exit_sem",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:newseg",
        "ipc/mqueue.c:mqueue_read_file",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491472,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505392,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:514",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:SYSC_kill",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:sys_getpgrp",
        "kernel/sys.c:sys_getppid",
        "kernel/sys.c:sys_getpid",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:SyS_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:posix_test_lock",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/mqueue.c:mqueue_read_file",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505392,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526064,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:514",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:do_send_specific",
        "kernel/signal.c:SYSC_kill",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:sys_getpgrp",
        "kernel/sys.c:sys_getppid",
        "kernel/sys.c:sys_getpid",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:SyS_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/locks.c:posix_test_lock",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/coredump.c:do_coredump",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:SYSC_semtimedop",
        "ipc/sem.c:SyS_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/mqueue.c:mqueue_read_file",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/condition.c:tomoyo_condition",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526064,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513728,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:515",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/locks.c:posix_test_lock",
        "fs/fuse/file.c:fuse_getlk",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513728,
      "name": "pid_vnr",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540384,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:384",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:sys_setsid",
        "kernel/sys.c:SyS_getsid",
        "kernel/sys.c:sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540384,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568048,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:409",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__x64_sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568048,
      "name": "pid_vnr",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605232,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:416",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__x64_sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605232,
      "name": "pid_vnr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629136,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629136,
      "name": "pid_vnr",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654688,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654688,
      "name": "pid_vnr",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685712,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:485",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_getpgrp",
        "kernel/sys.c:__ia32_sys_getpgid",
        "kernel/sys.c:__x64_sys_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:f_getown_ex",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685712,
      "name": "pid_vnr",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663968,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:486",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:f_getown_ex",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663968,
      "name": "pid_vnr",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579670784,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:486",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670784,
      "name": "pid_vnr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579748448,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:486",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748448,
      "name": "pid_vnr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852816,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:486",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852816,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993472,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:486",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sk_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993472,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047296,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:489",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sk_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047296,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089792,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:489",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:__do_sys_getpgrp",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/gpu/drm/drm_debugfs.c:drm_clients_info",
        "net/core/sock.c:sk_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089792,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490827632,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__arm64_sys_getsid",
        "kernel/sys.c:__arm64_sys_getpgrp",
        "kernel/sys.c:__arm64_sys_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490827632,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224859348,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:ksys_msgctl",
        "ipc/msg.c:ksys_msgctl",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:ksys_shmctl",
        "ipc/shm.c:ksys_shmctl",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "sound/core/control.c:snd_ctl_elem_info_user",
        "sound/core/pcm.c:snd_pcm_substream_proc_status_read",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859348,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283661840,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_getsid",
        "kernel/sys.c:sys_getpgrp",
        "kernel/sys.c:__se_sys_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283661840,
      "name": "pid_vnr",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271499858,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__se_sys_getsid",
        "kernel/sys.c:__se_sys_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:__se_sys_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/sem.c:semctl_main",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271499858,
      "name": "pid_vnr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631008,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631008,
      "name": "pid_vnr",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559344,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559344,
      "name": "pid_vnr",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628272,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628272,
      "name": "pid_vnr",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
pid_t pid_vnr(struct pid * pid)
```

```json
{
  "name": "pid_vnr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661856,
      "name": "pid_vnr",
      "external": true,
      "loc": "kernel/pid.c:419",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/sys.c:ksys_setsid",
        "kernel/sys.c:__ia32_sys_getsid",
        "kernel/sys.c:__x64_sys_getsid",
        "kernel/sys.c:do_getpgid",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:auditd_pid_vnr",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown",
        "fs/notify/fanotify/fanotify_user.c:fanotify_read",
        "ipc/msg.c:msgctl_stat",
        "ipc/msg.c:msgctl_stat",
        "ipc/sem.c:semctl_main",
        "ipc/shm.c:shmctl_stat",
        "ipc/shm.c:shmctl_stat",
        "ipc/mqueue.c:mqueue_read_file",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "net/core/sock.c:sock_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661856,
      "name": "pid_vnr",
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

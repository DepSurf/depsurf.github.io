# Function: <code>put_pid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491840,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:237",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:SyS_waitid",
        "kernel/exit.c:SyS_waitpid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "kernel/trace/ftrace.c:ftrace_pid_write",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:do_task_stat",
        "fs/proc/array.c:children_seq_next",
        "ipc/mqueue.c:__do_notify",
        "ipc/mqueue.c:remove_notification",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "drivers/usb/core/devio.c:usbdev_release",
        "net/core/sock.c:sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_destruct_scm",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491840,
      "name": "put_pid",
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505760,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:237",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:SyS_waitpid",
        "kernel/exit.c:SyS_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505760,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579526432,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:237",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:SyS_waitpid",
        "kernel/exit.c:SyS_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_ioctl",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526432,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514032,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:236",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/locks.c:locks_unlink_lock_ctx",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514032,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540528,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:89",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_delown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/ipv6/ip6_flowlabel.c:fl_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540528,
      "name": "put_pid",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568432,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:101",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/ipv6/ip6_flowlabel.c:fl_free",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568432,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579605520,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:101",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_destruct_scm",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/ipv6/ip6_flowlabel.c:fl_free",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_create",
        "net/xdp/xdp_umem.c:xdp_umem_release_deferred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579605520,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629280,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629280,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654832,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654832,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579686785,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:104",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:release_task",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_delown",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop_slow",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tiocspgrp",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:change_console",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:copy_peercred",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686080,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579686176,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665052,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:105",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:release_task",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid",
        "kernel/usermode_driver.c:umd_cleanup",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/audit.c:auditd_conn_free",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_delown",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop_slow",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_setactivate",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:copy_peercred",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664368,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579664464,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579672002,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:105",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:release_task",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid",
        "kernel/usermode_driver.c:umd_cleanup",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/audit.c:auditd_conn_free",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_delown",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop_slow",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:change_console",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671184,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579671280,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579753075,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:105",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:release_task",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid",
        "kernel/usermode_driver.c:umd_cleanup",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/audit.c:auditd_conn_free",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/madvise.c:__do_sys_process_madvise",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_delown",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop_slow",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:change_console",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579748864,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071579748960,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579858346,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:105",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:delayed_put_pid",
        "kernel/usermode_driver.c:umd_cleanup",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/audit.c:auditd_conn_free",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_delown",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop_slow",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:change_console",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853280,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579853408,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999530,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:105",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:delayed_put_pid",
        "kernel/usermode_driver.c:umd_cleanup",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/audit.c:auditd_conn_free",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_delown",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop_slow",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:__shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:__shm_open",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:change_console",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/bpfilter/sockopt.c:bpfilter_mbox_request",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994128,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579994272,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048979,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:108",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:delayed_put_pid",
        "kernel/usermode_driver.c:umd_cleanup",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-timers.c:posix_timer_unhash_and_free",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/audit.c:auditd_conn_free",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_delown",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/base.c:proc_pid_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop_slow",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:__shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:__shm_open",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:change_console",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sk_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047952,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580048096,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091475,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:108",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "kernel/fork.c:kernel_clone",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/exit.c:release_task",
        "kernel/exit.c:release_task",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:pidfd_get_task",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:do_timer_create",
        "kernel/time/posix-timers.c:posix_timer_unhash_and_free",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timer_del",
        "kernel/audit.c:auditd_conn_free",
        "kernel/bpf/task_iter.c:bpf_iter_attach_task",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_delown",
        "fs/notify/fanotify/fanotify.c:fanotify_free_event",
        "fs/proc/inode.c:proc_free_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:__shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:__shm_open",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "io_uring/waitid.c:io_waitid",
        "io_uring/waitid.c:io_waitid",
        "io_uring/waitid.c:io_waitid_complete",
        "io_uring/waitid.c:io_waitid_complete",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/n_tty.c:isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:change_console",
        "drivers/tty/vt/vt_ioctl.c:complete_change_console",
        "drivers/tty/vt/vt_ioctl.c:vc_SAK",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_k_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/gpu/drm/drm_file.c:drm_file_update_pid",
        "drivers/gpu/drm/drm_file.c:drm_file_free",
        "drivers/gpu/drm/drm_file.c:drm_file_alloc",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/sock.c:sk_getsockopt",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:__unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580090448,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071580090592,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490828728,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__arm64_sys_pidfd_open",
        "kernel/pid.c:__arm64_sys_pidfd_open",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vcpu_ioctl",
        "virt/kvm/kvm_main.c:kvm_vcpu_uninit",
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__arm64_sys_pidfd_open",
        "kernel/pid.c:__arm64_sys_pidfd_open",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490828424,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446603336490828520,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224862052,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:delayed_put_pid"
      ],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:ksys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:__shm_open",
        "ipc/mqueue.c:do_mq_timedsend",
        "ipc/mqueue.c:remove_notification",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "sound/core/control.c:snd_ctl_release",
        "sound/core/pcm.c:snd_pcm_detach_substream",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224859988,
      "name": "put_pid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 3224860060,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283662000,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283662000,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271499994,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:__se_sys_pidfd_open",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:__se_sys_semctl",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_signal",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271499994,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631152,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631152,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559488,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559488,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628416,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628416,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void put_pid(struct pid * pid)
```

```json
{
  "name": "put_pid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662000,
      "name": "put_pid",
      "external": true,
      "loc": "kernel/pid.c:103",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:_do_fork",
        "kernel/fork.c:pidfd_release",
        "kernel/exit.c:kernel_wait4",
        "kernel/exit.c:kernel_waitid",
        "kernel/sysctl.c:proc_do_cad_pid",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:pidfd_create",
        "kernel/pid.c:delayed_put_pid",
        "kernel/time/posix-timers.c:release_posix_timer",
        "kernel/audit.c:auditd_conn_free",
        "fs/file_table.c:__fput",
        "fs/fcntl.c:f_modown",
        "fs/proc/inode.c:proc_evict_inode",
        "fs/proc/array.c:children_seq_stop",
        "fs/proc/array.c:children_seq_next",
        "fs/proc/array.c:do_task_stat",
        "ipc/msg.c:do_msgrcv",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:do_msgsnd",
        "ipc/msg.c:freeque",
        "ipc/msg.c:freeque",
        "ipc/sem.c:exit_sem",
        "ipc/sem.c:semctl_main",
        "ipc/sem.c:semctl_setval",
        "ipc/sem.c:freeary",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/sem.c:perform_atomic_semop",
        "ipc/shm.c:newseg",
        "ipc/shm.c:newseg",
        "ipc/shm.c:shm_close",
        "ipc/shm.c:shm_destroy",
        "ipc/shm.c:shm_destroy",
        "ipc/mqueue.c:remove_notification",
        "ipc/mqueue.c:__do_notify",
        "drivers/tty/tty_io.c:tty_do_resize",
        "drivers/tty/tty_io.c:__tty_fasync",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/tty_io.c:release_one_tty",
        "drivers/tty/n_tty.c:__isig",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/pty.c:pty_resize",
        "drivers/tty/vt/vt_ioctl.c:reset_vc",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/vt_ioctl.c:vt_ioctl",
        "drivers/tty/vt/keyboard.c:fn_spawn_con",
        "drivers/tty/vt/vt.c:vc_deallocate",
        "drivers/usb/core/devio.c:usbdev_release",
        "drivers/usb/core/devio.c:async_completed",
        "drivers/usb/core/devio.c:free_async",
        "net/core/sock.c:__sk_destruct",
        "net/core/scm.c:__scm_send",
        "net/core/scm.c:__scm_send",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_recvmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_stream_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_dgram_sendmsg",
        "net/unix/af_unix.c:unix_stream_connect",
        "net/unix/af_unix.c:unix_listen",
        "net/unix/af_unix.c:init_peercred",
        "net/unix/scm.c:unix_destruct_scm",
        "net/ipv6/ip6_flowlabel.c:fl_free_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662000,
      "name": "put_pid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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

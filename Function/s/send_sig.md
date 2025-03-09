# Function: <code>send_sig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431680,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1429",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/entry/common.c:syscall_trace_enter_phase2",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "kernel/auditsc.c:audit_log_exit",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/filemap.c:generic_file_write_iter",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:splice_to_pipe",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:SyS_tee",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431680,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444080,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1429",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/filemap.c:generic_file_write_iter",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:splice_to_pipe",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444080,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464448,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1435",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/filemap.c:generic_file_write_iter",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "drivers/tty/tty_io.c:__do_SAK",
        "drivers/tty/tty_io.c:__do_SAK",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464448,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452928,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1457",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/filemap.c:generic_file_write_iter",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452928,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579481248,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1458",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/filemap.c:generic_file_write_iter",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:SyS_tee",
        "fs/splice.c:SyS_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481248,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497456,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1456",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/filemap.c:generic_file_write_iter",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497456,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530928,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1543",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530928,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557296,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1612",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:handle_swbp",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557296,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583440,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1617",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:handle_swbp",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583440,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617568,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1613",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__syscall_return_slowpath",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "mm/filemap.c:generic_write_check_limits",
        "fs/exec.c:exec_binprm",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:wait_for_space",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "fs/io-wq.c:io_wq_worker_cancel",
        "fs/io-wq.c:io_wqe_worker_send_sig",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617568,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597872,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1614",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "fs/read_write.c:generic_write_check_limits",
        "fs/exec.c:exec_binprm",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "fs/io-wq.c:io_wq_worker_cancel",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597872,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579603344,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1616",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "fs/read_write.c:generic_write_check_limits",
        "fs/exec.c:exec_binprm",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603344,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678496,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1642",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "fs/read_write.c:generic_write_check_limits",
        "fs/exec.c:exec_binprm",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678496,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772592,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1643",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "fs/read_write.c:generic_write_check_limits",
        "fs/exec.c:exec_binprm",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772592,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904688,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1644",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "fs/read_write.c:generic_write_check_limits",
        "fs/exec.c:exec_binprm",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904688,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954416,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1650",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "fs/read_write.c:generic_write_check_limits",
        "fs/exec.c:exec_binprm",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954416,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993712,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1656",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/entry/common.c:syscall_trace_enter",
        "kernel/cgroup/cgroup.c:__cgroup_kill",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "fs/read_write.c:generic_write_check_limits",
        "fs/exec.c:exec_binprm",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:splice_pipe_to_pipe",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993712,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490746912,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1617",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm64/kernel/ptrace.c:syscall_trace_enter",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:__arm64_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490746912,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224796672,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1617",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm/kernel/ptrace.c:syscall_trace_enter",
        "arch/arm/kernel/traps.c:arm_syscall",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:handle_swbp",
        "mm/filemap.c:generic_write_check_limits",
        "fs/exec.c:__do_execve_file",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "fs/binfmt_flat.c:calc_reloc",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224796672,
      "name": "send_sig",
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283571616,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1617",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave",
        "arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:handle_swbp",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283571616,
      "name": "send_sig",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271450956,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1617",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_exit",
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_enter",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "fs/exec.c:__do_execve_file",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:__se_sys_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "fs/binfmt_flat.c:calc_reloc",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271450956,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559744,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1617",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:handle_swbp",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559744,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488400,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1617",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:handle_swbp",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488400,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557024,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1617",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:handle_swbp",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557024,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int send_sig(int sig, struct task_struct * p, int priv)
```

```json
{
  "name": "send_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579590400,
      "name": "send_sig",
      "external": true,
      "loc": "kernel/signal.c:1617",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/kernel/uprobes.c:arch_uprobe_skip_sstep",
        "arch/x86/kernel/uprobes.c:arch_uprobe_post_xol",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/events/uprobes.c:handle_swbp",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/pipe.c:pipe_write",
        "fs/splice.c:do_tee",
        "fs/splice.c:do_splice",
        "fs/splice.c:add_to_pipe",
        "fs/splice.c:splice_to_pipe",
        "net/core/stream.c:sk_stream_error",
        "net/unix/af_unix.c:unix_stream_sendpage",
        "net/unix/af_unix.c:unix_stream_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579590400,
      "name": "send_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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

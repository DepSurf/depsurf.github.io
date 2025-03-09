# Function: <code>send_signal_locked</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579789878,
      "name": "send_signal_locked",
      "external": true,
      "loc": "kernel/signal.c:1219",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579771872,
      "name": "send_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579924214,
      "name": "send_signal_locked",
      "external": true,
      "loc": "kernel/signal.c:1220",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579903904,
      "name": "send_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579974118,
      "name": "send_signal_locked",
      "external": true,
      "loc": "kernel/signal.c:1224",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953632,
      "name": "send_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
```

```json
{
  "name": "send_signal_locked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580013526,
      "name": "send_signal_locked",
      "external": true,
      "loc": "kernel/signal.c:1214",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:kdb_send_sig"
      ],
      "caller_func": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:do_send_sig_info",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_process_timers",
        "kernel/time/posix-cpu-timers.c:check_cpu_itimer",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "kernel/time/posix-cpu-timers.c:check_thread_timers",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992928,
      "name": "send_signal_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int send_signal_locked(int sig, struct kernel_siginfo * info, struct task_struct * t, enum pid_type type)
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

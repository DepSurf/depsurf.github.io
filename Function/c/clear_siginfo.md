# Function: <code>clear_siginfo</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861013,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578865793,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579034769,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101677,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:send_sigtrap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303473,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "arch/x86/kernel/umip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/umip.c:force_sig_info_umip_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323587,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:force_sig_info_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497896,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_kill",
        "kernel/signal.c:copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580022821,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330949,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656041,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909641,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586609379,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:19",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_remove",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579531346,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580069877,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580384517,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581742351,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018195,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763890,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "drivers/usb/core/devio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/devio.c:usbdev_notify",
        "drivers/usb/core/devio.c:async_completed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579557869,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580115048,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580437157,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581859617,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583199472,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579583997,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580164360,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485925,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931969,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305264,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579618104,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580224104,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580575684,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582161761,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583636478,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579598424,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580138671,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/entry/syscall_user_dispatch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580208360,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580564948,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582208203,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758640,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579603896,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580143519,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/entry/syscall_user_dispatch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580217589,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580567457,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582233179,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782768,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579679176,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:force_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580287167,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/entry/syscall_user_dispatch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580365490,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551675,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584144992,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579773586,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580460437,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/entry/syscall_user_dispatch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580575193,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583080714,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584745765,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579905778,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580707637,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/entry/syscall_user_dispatch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836217,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583648298,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585440437,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579955506,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580784725,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/entry/syscall_user_dispatch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919736,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865482,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585671164,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579994802,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:21",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__do_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:send_sig_fault_trapno",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_seccomp",
        "kernel/signal.c:send_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_exit_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:__send_signal_locked",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873989,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:21",
      "file": "kernel/entry/syscall_user_dispatch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581010344,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:21",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072522,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:21",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585917948,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:21",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clear_siginfo(kernel_siginfo_t * info)
```

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490747608,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__arm64_sys_pidfd_send_signal",
        "kernel/signal.c:__arm64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": [
        "kernel/signal.c:__send_signal"
      ]
    },
    {
      "addr": 18446603336491385372,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491761652,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493413232,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495044908,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490723936,
      "name": "clear_siginfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224797344,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 3225380300,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3225715368,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 3226999032,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3228449708,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:do_mq_timedsend"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283572400,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284326000,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284804552,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286974280,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288935424,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "arch/riscv/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271451426,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__se_sys_pidfd_send_signal",
        "kernel/signal.c:__se_sys_kill",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault_to_task",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:collect_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271868272,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272086412,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter",
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273123250,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274319364,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579560301,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580133560,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580454725,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900705,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583274000,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579488957,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580078856,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580401797,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838657,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583211136,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579557581,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580124632,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580445973,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892017,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258032,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_siginfo",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579590973,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_tkill",
        "kernel/signal.c:__ia32_sys_pidfd_send_signal",
        "kernel/signal.c:__x64_sys_pidfd_send_signal",
        "kernel/signal.c:__ia32_sys_kill",
        "kernel/signal.c:__x64_sys_kill",
        "kernel/signal.c:post_copy_siginfo_from_user32",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:ptrace_do_notify",
        "kernel/signal.c:do_notify_parent_cldstop",
        "kernel/signal.c:do_notify_parent",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:send_sig_mceerr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:send_sig_fault",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sig",
        "kernel/signal.c:kill_pid_usb_asyncio",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__send_signal",
        "kernel/signal.c:__dequeue_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580176778,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/time/posix-timers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/posix-timers.c:do_timer_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501605,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_init_siginfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962281,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigio_to_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353936,
      "name": "clear_siginfo",
      "external": false,
      "loc": "include/linux/signal.h:20",
      "file": "ipc/mqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_notify"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void clear_siginfo(kernel_siginfo_t * info)
```
</details>
</li>
</ul>

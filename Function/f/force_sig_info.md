# Function: <code>force_sig_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int force_sig_info(int sig, struct siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579430944,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1160",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/ptrace.c:send_sigtrap",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/fault.c:force_sig_info_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/seccomp.c:seccomp_send_sigsys",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430944,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int force_sig_info(int sig, struct siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443344,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1160",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:send_sigtrap",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/fault.c:force_sig_info_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/seccomp.c:seccomp_send_sigsys",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443344,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int force_sig_info(int sig, struct siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579463712,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1166",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:send_sigtrap",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/fault.c:force_sig_info_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/seccomp.c:seccomp_send_sigsys",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463712,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int force_sig_info(int sig, struct siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452192,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1180",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:send_sigtrap",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/fault.c:force_sig_info_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/seccomp.c:seccomp_send_sigsys",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452192,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int force_sig_info(int sig, struct siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480512,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1181",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:send_sigtrap",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/kernel/umip.c:force_sig_info_umip_fault",
        "arch/x86/mm/fault.c:force_sig_info_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/seccomp.c:seccomp_send_sigsys",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480512,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int force_sig_info(int sig, struct siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496752,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1189",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:send_sigtrap",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/kernel/umip.c:force_sig_info_umip_fault",
        "arch/x86/mm/fault.c:force_sig_info_fault",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/seccomp.c:seccomp_send_sigsys",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496752,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int force_sig_info(int sig, struct kernel_siginfo * info, struct task_struct * t)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530224,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1272",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig_fault",
        "kernel/signal.c:force_sigsegv",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530224,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579559694,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1334",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558800,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579585822,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584928,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579621838,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621248,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579602142,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1340",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601552,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579607758,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1342",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch",
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607056,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579683951,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1353",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_perf",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr"
      ],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682416,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579780847,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1354",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr"
      ],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777312,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579913567,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1355",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr"
      ],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909840,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579963359,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1359",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr"
      ],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959632,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002639,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1360",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:force_sig_fault_trapno",
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr"
      ],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998880,
      "name": "force_sig_info",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490749572,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490748480,
      "name": "force_sig_info",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224798872,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224797692,
      "name": "force_sig_info",
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283574628,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283573504,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271452428,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271451742,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579562126,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561232,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579490782,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489888,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579559406,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558512,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int force_sig_info(struct kernel_siginfo * info)
```

```json
{
  "name": "force_sig_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579592798,
      "name": "force_sig_info",
      "external": true,
      "loc": "kernel/signal.c:1339",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sig_ptrace_errno_trap",
        "kernel/signal.c:force_sig_pkuerr",
        "kernel/signal.c:force_sig_bnderr",
        "kernel/signal.c:force_sig_mceerr",
        "kernel/signal.c:force_sig"
      ],
      "caller_func": [
        "kernel/seccomp.c:__seccomp_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591904,
      "name": "force_sig_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct siginfo * info</code> ➡️ <code>struct kernel_siginfo * info</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int sig</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct * t</code>
</li>
<li>
<b>Param reordered. </b>
<code>sig, info, t</code> ➡️ <code>info</code>
</li>
</ul>
</details>
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

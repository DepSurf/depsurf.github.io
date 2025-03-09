# Function: <code>force_sig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig, struct task_struct * p)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431168,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1435",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "mm/memory-failure.c:memory_failure",
        "drivers/tty/tty_io.c:__do_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431168,
      "name": "force_sig",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig, struct task_struct * p)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579446466,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1435",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "mm/memory-failure.c:memory_failure",
        "drivers/tty/tty_io.c:__do_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443568,
      "name": "force_sig",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig, struct task_struct * p)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579466834,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1441",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_handle_bd_fault",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "mm/memory-failure.c:memory_failure",
        "drivers/tty/tty_io.c:__do_SAK"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463936,
      "name": "force_sig",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig, struct task_struct * p)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579455330,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1463",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/pid_namespace.c:reboot_pid_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452416,
      "name": "force_sig",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig, struct task_struct * p)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579483650,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1464",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/pid_namespace.c:reboot_pid_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480736,
      "name": "force_sig",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig, struct task_struct * p)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579500146,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1462",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "mm/memory-failure.c:kill_procs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496976,
      "name": "force_sig",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig, struct task_struct * p)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533794,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1549",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530448,
      "name": "force_sig",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558832,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1618",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:force_sigsegv",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558832,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584960,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:force_sigsegv",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584960,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579622123,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1619",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/common.c:__prepare_exit_to_usermode",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:handle_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621280,
      "name": "force_sig",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579602427,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1620",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:handle_trampoline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601584,
      "name": "force_sig",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579608043,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1622",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:force_sigsegv"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607088,
      "name": "force_sig",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579683915,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1648",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/tlb.c:l1d_flush_force_sigbus",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683648,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579780822,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1649",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:gp_user_force_sig_segv",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/tlb.c:l1d_flush_force_sigbus",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778672,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579913542,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1650",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/tlb.c:l1d_flush_force_sigbus",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911360,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579963334,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1656",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/tlb.c:l1d_flush_force_sigbus",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961152,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580002614,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1662",
      "file": "kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done"
      ],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:exc_virtualization_exception",
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:exc_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/tlb.c:l1d_flush_force_sigbus",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "security/safesetid/lsm.c:safesetid_task_fix_setgroups",
        "security/safesetid/lsm.c:safesetid_task_fix_setgid",
        "security/safesetid/lsm.c:safesetid_task_fix_setuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000400,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490748528,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:force_sigsegv",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490748528,
      "name": "force_sig",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224797736,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/signal.c:addr_limit_check_failed",
        "arch/arm/kernel/signal.c:sys_rt_sigreturn",
        "arch/arm/kernel/signal.c:sys_sigreturn",
        "kernel/signal.c:force_sigsegv",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224797736,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283573536,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn",
        "arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn",
        "arch/powerpc/kernel/signal.c:do_notify_resume",
        "arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:force_sigsegv",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283573536,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271451786,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/signal.c:sys_rt_sigreturn",
        "kernel/signal.c:force_sigsegv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271451786,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579561264,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:force_sigsegv",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579561264,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489920,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:force_sigsegv",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489920,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579558544,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:force_sigsegv",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558544,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void force_sig(int sig)
```

```json
{
  "name": "force_sig",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591936,
      "name": "force_sig",
      "external": true,
      "loc": "kernel/signal.c:1623",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/signal.c:signal_fault",
        "arch/x86/kernel/traps.c:do_general_protection",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/uprobes.c:arch_uretprobe_hijack_return_addr",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "kernel/signal.c:force_sigsegv",
        "kernel/signal.c:force_sigsegv",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:handle_swbp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591936,
      "name": "force_sig",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * p</code>
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

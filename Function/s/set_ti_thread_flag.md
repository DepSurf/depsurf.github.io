# Function: <code>set_ti_thread_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579029522,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:copy_thread_tls",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034519,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038632,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048317,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:sys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078581,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098184,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173080,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258377,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336973,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580465413,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446744071579415920,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579423033,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:recalc_sigpending_tsk",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:ptrace_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579542393,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647483,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/sched/idle.c:cpu_startup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990332,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580058340,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137651,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580154994,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580453719,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580456866,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582879908,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536181,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/idle/intel_idle.c:intel_idle_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583957557,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584382384,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585906809,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586409359,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:set_tx_maxrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586786855,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587025843,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:69",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580465413,
      "name": "set_ti_thread_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579025426,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:copy_thread_tls",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029829,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034572,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044493,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:sys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074551,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097879,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173568,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257785,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342315,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580542505,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579428208,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441943,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553747,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663105,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpu_startup_entry",
        "kernel/sched/idle.c:cpu_startup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580023203,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580091531,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580173275,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580189394,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532190,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532354,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583165983,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583857004,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_freeze",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291504,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584717328,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586306441,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586852188,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:set_tx_maxrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587235293,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587474086,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:70",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542505,
      "name": "set_ti_thread_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579025426,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029472,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034404,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043565,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:sys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588100967,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096051,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588101449,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271305,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358164,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606550,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579447744,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462311,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578463,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579686921,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580057421,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580131831,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580213903,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580230036,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580596165,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580596322,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278047,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583996038,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_freeze",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584473575,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584906464,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588102217,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587043260,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:set_tx_maxrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587435837,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587677350,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:41",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606550,
      "name": "set_ti_thread_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579017634,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579021887,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026471,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035981,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:sys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588326567,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087939,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588327081,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268000,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579352020,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386416,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579435576,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450807,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561788,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579673129,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865263,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580068907,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137527,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580223803,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580239732,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580625975,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580626114,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583333201,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044198,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_freeze",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584599987,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584991600,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588327897,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587171240,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:set_tx_maxrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587572454,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587816590,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386416,
      "name": "set_ti_thread_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579021170,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579025266,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579030311,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579043849,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:sys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892695,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098719,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588893212,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284985,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579378391,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397539,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413293,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579433120,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463848,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479191,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579591058,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579703817,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579798044,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579908783,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580045912,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121537,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580190102,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580273525,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580290964,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580486719,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size",
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580693438,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580706951,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580707090,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580757449,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417639,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448327,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639195,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680951,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836794,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849362,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583161867,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516497,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584308521,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585011939,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585413552,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588894057,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587386007,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_sock_ioctl",
        "net/socket.c:kernel_sock_ioctl",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587676591,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587723109,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588096246,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588189166,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588346350,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588539319,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:57",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_renew_options_kern",
        "net/ipv6/exthdrs.c:ipv6_renew_options_kern"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413293,
      "name": "set_ti_thread_flag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579025791,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579030082,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034441,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048570,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589270927,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104255,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589271418,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296457,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392407,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424110,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579448336,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477402,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495380,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589250540,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648198,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831596,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943676,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580104205,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580181101,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249958,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580335913,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580352228,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574044,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size",
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580810821,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580825440,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580839173,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580839503,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580852318,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580893517,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576727,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606119,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802383,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842263,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016022,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582030766,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367355,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583729764,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584528586,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585246016,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585656160,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589272254,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587693141,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588006545,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057570,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/compat.c:__compat_sys_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588449951,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588540445,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588704835,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943676,
      "name": "set_ti_thread_flag.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579030063,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034770,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039241,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053450,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589513663,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109887,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127397,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:task_update_spec_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589514266,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320985,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420423,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457224,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579481808,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579510746,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579528884,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492846,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685830,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579878332,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579978341,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_check_callbacks",
        "kernel/rcu/tree.c:rcu_check_callbacks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990764,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580151682,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580229139,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount",
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580303286,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391743,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580408468,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877461,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892206,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907621,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908159,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920782,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968157,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581662487,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691399,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889388,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930055,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582103974,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118830,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583486107,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837727,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584625738,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585365424,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585788320,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589515229,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587827237,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588166977,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588233362,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/compat.c:__compat_sys_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643215,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588738925,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588923155,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579990764,
      "name": "set_ti_thread_flag.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579038031,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042289,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046914,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061146,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589972767,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100192,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579103582,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119806,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138037,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:task_update_spec_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589973384,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336169,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579436796,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474040,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579499839,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530336,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553636,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589953813,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719558,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913226,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580001596,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032943,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580049725,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197798,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580277455,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580279704,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355521,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580443597,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461357,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580911272,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973798,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989718,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581005336,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006015,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016789,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063805,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581770631,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809514,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582013888,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070954,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190331,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266223,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280959,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582405175,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583242779,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672203,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584028063,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584824213,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585579127,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586019296,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589974351,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588132629,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588488993,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589055456,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589171160,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589366156,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579040431,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044657,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049154,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063251,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590200175,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102176,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105223,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121694,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140149,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:task_update_spec_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590200792,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579340377,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579439708,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501062,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579525954,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556488,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579780,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590181355,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579762070,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579963322,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580051772,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083663,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580098829,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580246021,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580325599,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580327816,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580404289,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580492777,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580510269,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964120,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027926,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043702,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581060296,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581060847,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072053,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119773,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842855,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581882106,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091856,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582148538,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270633,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582365613,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380045,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582504135,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348603,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583779211,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584132058,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584959957,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585720039,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586167040,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590201759,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588339301,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588696673,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589279952,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589395784,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589591244,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050847,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__set_personality_ia32",
        "arch/x86/kernel/process_64.c:__set_personality_x32",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059376,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071044,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/ioport.c:io_bitmap_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591216223,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114549,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118962,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136430,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156742,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163627,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_warn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273977,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369804,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579528392,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_seccomp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579558137,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579587752,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579616512,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:calculate_sigpending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579701394,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579754059,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:prepare_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795606,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:cpuidle_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580118202,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_sched_exp_online_cleanup",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580143180,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580161374,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580398434,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580400380,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580481120,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580578477,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_strict",
        "kernel/seccomp.c:seccomp_attach_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580597101,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147367,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223090,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581241432,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581241967,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581253027,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303835,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:copy_from_user_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582063638,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115232,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:begin_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582326044,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583684486,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584529323,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655067,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586449815,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586931272,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591217501,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589196909,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589561998,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/core/net-sysfs.c:phys_port_id_show",
        "net/core/net-sysfs.c:proto_down_store",
        "net/core/net-sysfs.c:group_store",
        "net/core/net-sysfs.c:ifalias_store",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store",
        "net/core/net-sysfs.c:gro_flush_timeout_store",
        "net/core/net-sysfs.c:flags_store",
        "net/core/net-sysfs.c:mtu_store",
        "net/core/net-sysfs.c:duplex_show",
        "net/core/net-sysfs.c:carrier_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590253282,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590595130,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_fixup_linkdown",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053375,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075332,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/ioport.c:io_bitmap_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591711071,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114630,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118228,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134462,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153982,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160859,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_warn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281305,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368812,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579596784,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:calculate_sigpending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739067,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:prepare_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579786422,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:cpuidle_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579930603,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:ipi_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580099354,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_sched_exp_online_cleanup",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591310327,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580385847,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580387660,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284200,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284335,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581295161,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583806118,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584639218,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585781275,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586564300,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587018424,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591711933,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589574860,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/core/net-sysfs.c:phys_port_id_show",
        "net/core/net-sysfs.c:proto_down_store",
        "net/core/net-sysfs.c:group_store",
        "net/core/net-sysfs.c:ifalias_store",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store",
        "net/core/net-sysfs.c:gro_flush_timeout_store",
        "net/core/net-sysfs.c:flags_store",
        "net/core/net-sysfs.c:mtu_store",
        "net/core/net-sysfs.c:duplex_show",
        "net/core/net-sysfs.c:carrier_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590306178,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590655258,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_fixup_linkdown",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579060303,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082308,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/ioport.c:io_bitmap_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591658463,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121286,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124866,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140860,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161326,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167899,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_warn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284064,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579373100,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602272,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:calculate_sigpending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579748835,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:prepare_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_fork",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579794550,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:cpuidle_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938971,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:ipi_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591250132,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591252803,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580388778,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580390591,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302152,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302287,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313035,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583830374,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584667138,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585661858,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586449244,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586902056,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591659325,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589473598,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:traffic_class_show",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/core/net-sysfs.c:phys_port_id_show",
        "net/core/net-sysfs.c:ifalias_store",
        "net/core/net-sysfs.c:duplex_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590222048,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590583210,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:86",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579081551,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105268,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/ioport.c:io_bitmap_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592832111,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147015,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_flush_thread",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150697,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579167758,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191838,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate",
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200779,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_warn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327869,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434396,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677424,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:calculate_sigpending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579833611,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:prepare_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890518,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:cpuidle_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580063995,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:ipi_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592144204,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592149074,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580550874,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580552655,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581546744,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581546879,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558267,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584193494,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585083558,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586140431,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586976186,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587463748,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592833053,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590212309,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:traffic_class_show",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/core/net-sysfs.c:phys_port_name_show",
        "net/core/net-sysfs.c:phys_port_id_show",
        "net/core/net-sysfs.c:ifalias_store",
        "net/core/net-sysfs.c:duplex_show",
        "net/core/net-sysfs.c:speed_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591004698,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591399546,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579109983,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135254,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/ioport.c:io_bitmap_exit",
        "arch/x86/kernel/ioport.c:io_bitmap_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594741471,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187418,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_flush_thread",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192931,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213212,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240228,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387860,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503683,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579781439,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:calculate_sigpending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579949307,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:prepare_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580085462,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:idle_inject_timer_fn",
        "kernel/sched/build_policy.c:do_idle",
        "kernel/sched/build_policy.c:cpuidle_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580151467,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408800,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_flavor_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:print_cpu_stall"
      ]
    },
    {
      "addr": 18446744071593921527,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580749367,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751310,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581897653,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581897823,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910449,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584794710,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585809739,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371588,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588273051,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588783544,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594744300,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591786993,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:traffic_class_show",
        "net/core/net-sysfs.c:threaded_store",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/core/net-sysfs.c:phys_port_name_show",
        "net/core/net-sysfs.c:phys_port_id_show",
        "net/core/net-sysfs.c:proto_down_store",
        "net/core/net-sysfs.c:group_store",
        "net/core/net-sysfs.c:ifalias_store",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store",
        "net/core/net-sysfs.c:gro_flush_timeout_store",
        "net/core/net-sysfs.c:tx_queue_len_store",
        "net/core/net-sysfs.c:flags_store",
        "net/core/net-sysfs.c:mtu_store",
        "net/core/net-sysfs.c:duplex_show",
        "net/core/net-sysfs.c:speed_show",
        "net/core/net-sysfs.c:carrier_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592650905,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593075801,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391536,
      "name": "set_ti_thread_flag.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071593921527,
      "name": "set_ti_thread_flag.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579147631,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176518,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/ioport.c:io_bitmap_exit",
        "arch/x86/kernel/ioport.c:io_bitmap_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596493775,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243134,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_reset_fpregs",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249081,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269468,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299700,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466340,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579601331,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579914175,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:calculate_sigpending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580014518,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580108315,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:prepare_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580256934,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:idle_inject_timer_fn",
        "kernel/sched/build_policy.c:do_idle",
        "kernel/sched/build_policy.c:cpuidle_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580324603,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580641924,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580679530,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_copy_process",
        "kernel/livepatch/transition.c:klp_start_transition",
        "kernel/livepatch/transition.c:klp_start_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026711,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028750,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582331157,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582331359,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345441,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585492294,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586591289,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588620084,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589688076,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590278168,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596496972,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593580465,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:traffic_class_show",
        "net/core/net-sysfs.c:threaded_store",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/core/net-sysfs.c:phys_port_name_show",
        "net/core/net-sysfs.c:phys_port_id_show",
        "net/core/net-sysfs.c:proto_down_store",
        "net/core/net-sysfs.c:group_store",
        "net/core/net-sysfs.c:ifalias_store",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store",
        "net/core/net-sysfs.c:gro_flush_timeout_store",
        "net/core/net-sysfs.c:tx_queue_len_store",
        "net/core/net-sysfs.c:flags_store",
        "net/core/net-sysfs.c:mtu_store",
        "net/core/net-sysfs.c:duplex_show",
        "net/core/net-sysfs.c:speed_show",
        "net/core/net-sysfs.c:carrier_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594517417,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594969977,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579149199,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179894,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/ioport.c:io_bitmap_exit",
        "arch/x86/kernel/ioport.c:io_bitmap_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240396,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246715,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_reset_fpregs",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255741,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275788,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306054,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579614083,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579963967,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:calculate_sigpending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068262,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580230822,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_mm_cid_after_execve",
        "kernel/sched/core.c:prepare_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322934,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:idle_inject_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391931,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710068,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756042,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_copy_process",
        "kernel/livepatch/transition.c:klp_start_transition",
        "kernel/livepatch/transition.c:klp_start_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581115063,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117118,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582532373,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582532575,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582548092,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585724031,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586848099,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589992692,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590598728,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594052097,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:traffic_class_show",
        "net/core/net-sysfs.c:threaded_store",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/core/net-sysfs.c:phys_port_name_show",
        "net/core/net-sysfs.c:phys_port_id_show",
        "net/core/net-sysfs.c:proto_down_store",
        "net/core/net-sysfs.c:group_store",
        "net/core/net-sysfs.c:ifalias_store",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store",
        "net/core/net-sysfs.c:gro_flush_timeout_store",
        "net/core/net-sysfs.c:tx_queue_len_store",
        "net/core/net-sysfs.c:flags_store",
        "net/core/net-sysfs.c:mtu_store",
        "net/core/net-sysfs.c:duplex_show",
        "net/core/net-sysfs.c:speed_show",
        "net/core/net-sysfs.c:carrier_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594909305,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595362729,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579095103,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579178479,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209110,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:__ia32_sys_iopl",
        "arch/x86/kernel/ioport.c:__x64_sys_iopl",
        "arch/x86/kernel/ioport.c:ksys_ioperm",
        "arch/x86/kernel/ioport.c:io_bitmap_exit",
        "arch/x86/kernel/ioport.c:io_bitmap_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269239,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275339,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu_reset_fpregs",
        "arch/x86/kernel/fpu/core.c:fpu_clone",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285655,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305596,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336998,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ib_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set",
        "arch/x86/kernel/cpu/bugs.c:ssb_prctl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580003262,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:zap_other_threads",
        "kernel/signal.c:force_sig_info_to_task",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:complete_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:calculate_sigpending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580110902,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580279659,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_mm_cid_after_execve",
        "kernel/sched/core.c:prepare_task_switch",
        "kernel/sched/core.c:wake_up_new_task",
        "kernel/sched/core.c:sched_cgroup_fork",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580376870,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:idle_inject_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447787,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580776916,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_read_unlock_special",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841162,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_copy_process",
        "kernel/livepatch/transition.c:klp_start_transition",
        "kernel/livepatch/transition.c:klp_start_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213015,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215358,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582701349,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582701551,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718684,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971215,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587125424,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590331220,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590957672,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:online_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594842558,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_rxqs_show",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:xps_cpus_show",
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:traffic_class_show",
        "net/core/net-sysfs.c:threaded_store",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/core/net-sysfs.c:phys_port_name_show",
        "net/core/net-sysfs.c:phys_port_id_show",
        "net/core/net-sysfs.c:proto_down_store",
        "net/core/net-sysfs.c:group_store",
        "net/core/net-sysfs.c:ifalias_store",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_store",
        "net/core/net-sysfs.c:gro_flush_timeout_store",
        "net/core/net-sysfs.c:tx_queue_len_store",
        "net/core/net-sysfs.c:flags_store",
        "net/core/net-sysfs.c:mtu_store",
        "net/core/net-sysfs.c:duplex_show",
        "net/core/net-sysfs.c:speed_show",
        "net/core/net-sysfs.c:carrier_show",
        "net/core/net-sysfs.c:carrier_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595721042,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596203626,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:87",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_fixup_forwarding"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490185892,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:fpsimd_flush_cpu_state",
        "arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch",
        "arch/arm64/kernel/fpsimd.c:sve_set_vector_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490195016,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/process.c:set_tagged_addr_ctrl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490215372,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:sve_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490229792,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490336344,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/arm64/kernel/ssbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set",
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490528192,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/arm64/kvm/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp",
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490632828,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490668760,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490709308,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490738940,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:set_compat_user_sigmask",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503924256,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490940820,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491255840,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491472932,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:flush_module_icache",
        "kernel/module.c:flush_module_icache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491583988,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491587868,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491669760,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491769160,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491789408,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492310712,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492352508,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492399160,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492418596,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492435108,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__arm64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492490648,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493307796,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493357956,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493628004,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493697908,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493850788,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493961536,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493976044,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494129400,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495093116,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495581672,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495981340,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498413164,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498962848,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501476940,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/firmware/arm_sdei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_sdei.c:sdei_event_handler",
        "drivers/firmware/arm_sdei.c:sdei_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501833024,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__arm64_sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502259900,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502909928,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503049392,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503266084,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224415364,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/arm/kernel/elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/elf.c:elf_set_personality"
      ],
      "caller_func": []
    },
    {
      "addr": 3224710500,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3224770556,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3224790536,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:sigsuspend",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 3236534092,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 3224959144,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 3225264708,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 3225545772,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3225547920,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 3225624032,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3225717640,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225737216,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226302424,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 3226311896,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__se_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 3228486408,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3229322384,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 3231084976,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231533060,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3234999056,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 3235603304,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 3235933396,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282264456,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:user_enable_block_step",
        "arch/powerpc/kernel/ptrace.c:user_enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282291028,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/powerpc/kernel/signal_32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn",
        "arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn",
        "arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282298596,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/process.c:start_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282377244,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/powerpc/kernel/signal_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn",
        "arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282891676,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/powerpc/lib/sstep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/lib/sstep.c:emulate_loadstore"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283450588,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283491068,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283535248,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283555600,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283590816,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_compat_sys_times",
        "kernel/sys.c:__se_sys_times"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297771176,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283795976,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284156152,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284208740,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284240548,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/time/time.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/time.c:__se_sys_time32",
        "kernel/time/time.c:__se_sys_time"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284444128,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284565800,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284569644,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284677592,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284814116,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284839152,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285549816,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285581772,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285661296,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285686368,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285704248,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__se_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285776280,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286848484,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286903596,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286976204,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287218040,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287299804,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287467868,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287603140,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287618524,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287740088,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287807840,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288927932,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/shm.c:__se_compat_sys_shmat",
        "ipc/shm.c:__se_sys_shmat"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288994372,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289679612,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290206060,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291597856,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291872804,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:memory_lseek"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292108260,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294886924,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/cpuidle-pseries.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle-pseries.c:snooze_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294888548,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/cpuidle-powernv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle-powernv.c:snooze_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295231092,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295748172,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296577872,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296743656,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297007324,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271386426,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271432840,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271458080,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigsuspend",
        "kernel/signal.c:set_user_sigmask",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_and_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271549648,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:wake_up_nohz_cpu",
        "kernel/sched/core.c:resched_curr",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271571974,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271797226,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271992864,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271995404,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272061000,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272088020,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_attach_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272103780,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274355188,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:request_key_rcu",
        "security/keys/request_key.c:request_key_and_link"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275081308,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276070470,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276343950,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278495738,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store",
        "net/core/net-sysfs.c:phys_switch_id_show",
        "net/core/net-sysfs.c:phys_port_name_show",
        "net/core/net-sysfs.c:phys_port_id_show",
        "net/core/net-sysfs.c:ifalias_store",
        "net/core/net-sysfs.c:duplex_show",
        "net/core/net-sysfs.c:speed_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279004872,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279292158,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579040783,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579045009,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049506,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063603,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589802463,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102560,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105607,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122078,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140517,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:task_update_spec_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589803080,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336281,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435548,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474726,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579499618,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532792,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556084,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589783643,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579737990,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579932058,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580020508,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052399,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580068029,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580214821,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580294399,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580296616,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580373089,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461577,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580479069,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932920,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996774,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012550,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029144,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029695,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040901,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088621,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581811591,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850842,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060592,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117274,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582239369,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334349,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348781,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582472871,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317339,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747947,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584100794,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584910117,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585481063,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585927408,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589804047,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587946085,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303409,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588886128,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589001064,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589195612,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578973743,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977985,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983394,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996339,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589524895,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034976,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038023,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054046,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071669,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:task_update_spec_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589525496,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579364647,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403624,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579428498,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461572,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579484788,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589506132,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668406,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870330,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579961644,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997711,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580012845,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580162261,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580241759,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580243966,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580320257,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408627,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580426205,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580878984,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580942966,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958678,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975224,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975775,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604773586,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/context_tracking.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/context_tracking.c:context_tracking_cpu_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580988181,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035805,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749255,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788506,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581998144,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582054714,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177113,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272077,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286493,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410103,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254443,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685003,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584036494,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816021,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585350983,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585776544,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589526409,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587659189,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588016225,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588598064,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588724120,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588920604,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579040367,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044593,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049090,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063187,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590245871,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102112,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105159,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121630,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140069,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:task_update_spec_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590246488,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336201,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435468,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474646,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579499538,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530072,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579553364,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590227051,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579722438,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579923594,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012044,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_exp_need_qs",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580043935,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580059101,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206293,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580285647,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580287864,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580364337,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580452825,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470317,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924168,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580987974,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003750,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020344,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020895,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032101,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581079821,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802903,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842154,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051872,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107754,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229849,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582324829,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582339261,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582463351,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583731723,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084554,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911541,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585670439,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586117056,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590247455,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277861,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588635233,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589322512,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589437448,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589632476,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
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
  "name": "set_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579044031,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:__switch_to",
        "arch/x86/kernel/process_64.c:copy_thread_tls"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048321,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052872,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579067121,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ioport.c:ksys_ioperm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590296959,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106880,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/core.c:fpu__copy",
        "arch/x86/kernel/fpu/core.c:kernel_fpu_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110007,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126750,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145205,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:task_update_spec_tif"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297640,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344615,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:paravirt_start_context_switch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444652,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "arch/x86/ia32/ia32_signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/ia32/ia32_signal.c:ia32_restore_sigcontext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579506464,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532162,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562724,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579586596,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:signal_wake_up_state",
        "kernel/signal.c:calculate_sigpending",
        "kernel/signal.c:recalc_sigpending_tsk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590277405,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:set_task_cpu",
        "kernel/sched/core.c:resched_curr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579769862,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:idle_inject_timer_fn",
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579969610,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067475,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:__rcu_read_unlock",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_exp_handler",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580094703,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580109933,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258747,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580339509,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580341979,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:cgroup_leave_frozen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580419747,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580508487,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_set_mode_filter",
        "kernel/seccomp.c:seccomp_set_mode_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580526013,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984504,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048918,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581064950,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581081688,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_post_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_pre_sstep_notifier",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082239,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/user-return-notifier.c:user_return_notifier_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094565,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "kernel/rseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__ia32_sys_rseq",
        "kernel/rseq.c:__x64_sys_rseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141709,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581872119,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911738,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582123552,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582182250,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582306489,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404093,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418589,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582546119,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583395995,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/keys/request_key.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/request_key.c:cache_requested_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832603,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584187338,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017621,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778556,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586225664,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590298655,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588413013,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588775009,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:tx_maxrate_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589364384,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/devinet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/devinet.c:devinet_sysctl_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589482040,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589681436,
      "name": "set_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:53",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_sysctl_disable_policy",
        "net/ipv6/addrconf.c:addrconf_sysctl_ignore_routes_with_linkdown",
        "net/ipv6/addrconf.c:addrconf_sysctl_stable_secret",
        "net/ipv6/addrconf.c:addrconf_sysctl_addr_gen_mode",
        "net/ipv6/addrconf.c:addrconf_sysctl_proxy_ndp",
        "net/ipv6/addrconf.c:addrconf_sysctl_disable",
        "net/ipv6/addrconf.c:addrconf_sysctl_forward",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void set_ti_thread_flag(struct thread_info * ti, int flag)
```
</details>
</li>
</ul>

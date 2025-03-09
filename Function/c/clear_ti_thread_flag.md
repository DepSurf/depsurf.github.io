# Function: <code>clear_ti_thread_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void clear_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857904,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029535,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038323,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078700,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:exit_thread",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089043,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags",
        "arch/x86/kernel/ptrace.c:ptrace_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098245,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173176,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179563,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:common_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358784,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446744071579379521,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415930,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579423122,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587363564,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647214,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpu_startup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580024060,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580058210,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155161,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580453648,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_deny_signal",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580456825,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580486270,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399139,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536279,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle",
        "drivers/idle/intel_idle.c:intel_idle_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584233275,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584254412,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "drivers/char/tpm/tpm_tis.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585906861,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:74",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:poll_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358784,
      "name": "clear_ti_thread_flag",
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
void clear_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578858145,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579025439,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034351,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074670,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579093186,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ptrace_disable",
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098317,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173524,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179963,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:common_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365680,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579391866,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579431057,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579438194,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587865121,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663348,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:cpu_startup_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580056656,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580091404,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580189561,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580529300,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532315,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581578540,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856960,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_freeze",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584573240,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584595740,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586306493,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:75",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:poll_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365680,
      "name": "clear_ti_thread_flag",
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
void clear_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578858123,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579025436,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034183,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588101068,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579091266,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ptrace_disable",
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096471,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588101412,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383776,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579412220,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447574,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458565,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588079690,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687485,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580096729,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580131708,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580230201,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580593300,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580596283,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580637566,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663467,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583996001,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_freeze",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584755204,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584777113,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588102254,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:46",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:poll_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383776,
      "name": "clear_ti_thread_flag",
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
void clear_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578857765,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017649,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026263,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588326713,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579083138,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ptrace_disable",
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088359,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588327044,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371184,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579400039,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435558,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446197,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588306033,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579673683,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865887,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580102313,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137404,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580239897,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580623281,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580626087,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580669630,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717946,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584044161,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_freeze",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584835976,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584864401,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588327929,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/driver.c:poll_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371184,
      "name": "clear_ti_thread_flag",
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
void clear_ti_thread_flag(struct thread_info * ti, int flag)
```

```json
{
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578861013,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579021185,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579030103,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892844,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579093906,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ptrace_disable",
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099143,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588893172,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397968,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579428087,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463830,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474581,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588871405,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704430,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579909460,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154953,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580189979,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580291129,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580704193,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580707063,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580754690,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863561,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584308481,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585257140,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585283447,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588894099,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:62",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397968,
      "name": "clear_ti_thread_flag",
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862962,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579025804,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034119,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589271059,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099426,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ptrace_disable",
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104695,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589271378,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419379,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579443025,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579477388,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490917,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589250361,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648908,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943348,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580214602,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249835,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352392,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836513,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580839479,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580889679,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582044351,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584528546,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585521244,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589272275,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863010,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579030076,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038919,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589513797,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105026,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:ptrace_disable",
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110327,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589514226,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450637,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579476545,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579510732,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579524469,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589492667,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579686476,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579990436,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_switch_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580267055,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580303163,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408632,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904945,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908135,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580963391,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582132616,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584625698,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585645340,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589515368,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863557,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038044,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579046599,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589972908,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098692,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105170,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113680,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120279,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589973344,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468858,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494496,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530322,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561939,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589953623,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579720245,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032476,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580317896,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580355401,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461537,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004943,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581005989,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581060414,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582295017,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584824173,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585870445,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589974504,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863653,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040444,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048839,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590200316,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100676,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107016,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115600,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122167,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590200752,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494932,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579520517,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556470,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579588074,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590181165,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579762757,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083196,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580366728,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580404169,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580510449,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059903,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581060821,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581116190,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582393993,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584959917,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586013005,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590201840,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578866049,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:__prepare_exit_to_usermode",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579050743,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:__set_personality_ia32",
        "arch/x86/kernel/process_64.c:__set_personality_x32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059135,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:handle_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070351,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591216369,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113341,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu__clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119954,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126700,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136663,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273938,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527246,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579549852,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579587734,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579624104,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591199654,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579796623,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142831,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580440232,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580480988,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc",
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580597281,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581241039,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581241941,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581300014,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678352,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:zap_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655028,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586751629,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591217523,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579055871,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591649053,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:noist_exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074639,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591711156,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113629,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119913,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125308,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134695,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281266,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579505586,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579531068,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579604380,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591694588,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579787391,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580120063,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580138172,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:exit_to_user_mode_loop",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580139109,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/entry/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_work",
        "kernel/entry/kvm.c:xfer_to_guest_mode_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580428216,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283807,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284309,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581344014,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582747613,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:zap_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585781236,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586845709,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591711955,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579062943,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591592862,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:noist_exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081615,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591658545,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120285,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579126329,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579132556,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141399,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284025,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509025,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535308,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579610433,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591637115,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795529,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123567,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142988,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:exit_to_user_mode_loop",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580143938,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/entry/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work",
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580432664,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301759,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302261,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581363102,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582641798,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_cqring_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582659435,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wqe_worker",
        "fs/io-wq.c:io_worker_handle_work",
        "fs/io-wq.c:io_worker_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582776538,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:zap_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585661819,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586725789,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591659347,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:91",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579084159,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592764686,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:noist_exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104575,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592832190,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579145738,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151571,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579158892,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168343,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191743,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327830,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480727,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578129,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579607724,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579686317,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592811123,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579891465,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:cpuidle_idle_call",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580266297,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580286636,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:exit_to_user_mode_loop",
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580287596,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_work",
        "kernel/entry/kvm.c:xfer_to_guest_mode_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580596728,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545729,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581546853,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581610910,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970213,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_register",
        "fs/io_uring.c:__x64_sys_io_uring_register",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_uring_try_cancel_requests",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582984233,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:io_wqe_worker",
        "fs/io-wq.c:io_worker_handle_work",
        "fs/io-wq.c:io_worker_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583103754,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:zap_threads"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586140392,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587277270,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592833075,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579112959,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594657756,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:noist_exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134901,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594741558,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187658,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191431,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:fpregs_restore_userregs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579194839,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpregs_restore_userregs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204156,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579213991,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240207,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387807,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579559771,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579668962,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579700571,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784475,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594712981,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580104472,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:do_idle",
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "kernel/sched/build_policy.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580436547,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459855,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580460914,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580799340,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581896657,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581897791,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581971118,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583582211,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:coredump_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586024544,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__ia32_sys_io_uring_register",
        "io_uring/io_uring.c:__x64_sys_io_uring_register",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_rsrc_ref_quiesce",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_cqring_wait",
        "io_uring/io_uring.c:io_sq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586034591,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:io_wqe_worker",
        "io_uring/io-wq.c:io_worker_handle_work",
        "io_uring/io-wq.c:io_worker_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587371537,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588586676,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594744322,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579151695,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596391260,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:noist_exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176133,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596493862,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243578,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249898,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253024,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpstate_realloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259436,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269815,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299679,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466287,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579666954,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789010,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579825979,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579917251,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596460005,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580277560,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/sched/build_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_policy.c:do_idle",
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "kernel/sched/build_policy.c:cpuidle_idle_call",
        "kernel/sched/build_policy.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580679566,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_copy_process",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580707007,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580708174,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084460,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582329745,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582331311,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582405278,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584185603,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:coredump_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586752661,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586816645,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586863461,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588620033,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590042453,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596496994,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579153807,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596921484,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:noist_exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179509,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579240390,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249930,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256546,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259521,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579265660,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579276135,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306033,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579680887,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836482,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579875039,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579967059,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580127896,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/vhost_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/vhost_task.c:vhost_task_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597001365,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756078,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_copy_process",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580783839,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:exit_to_user_mode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580785503,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176204,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582530977,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582532527,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582611294,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584413195,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:coredump_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587017349,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587082981,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587129637,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590351867,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579183103,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597847212,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:noist_exc_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208725,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ioport.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579269233,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279354,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:fpregs_lock_and_load",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return",
        "arch/x86/kernel/fpu/core.c:fpu_clone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286434,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289839,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579295484,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305943,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:set_task_blockstep",
        "arch/x86/kernel/step.c:enable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336977,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715335,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876485,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912909,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:__exit_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006387,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580172376,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/vhost_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/vhost_task.c:vhost_task_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597930692,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841198,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_copy_process",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597866919,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580874767,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/entry/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281884,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582700017,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582701503,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582782862,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584633931,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:coredump_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587297317,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587362309,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587415781,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590693403,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:92",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490180536,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm64/kernel/debug-monitors.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/debug-monitors.c:user_disable_single_step"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490189192,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm64/kernel/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/fpsimd.c:fpsimd_update_current_state",
        "arch/arm64/kernel/fpsimd.c:fpsimd_restore_current_state",
        "arch/arm64/kernel/fpsimd.c:fpsimd_flush_thread",
        "arch/arm64/kernel/fpsimd.c:fpsimd_thread_switch",
        "arch/arm64/kernel/fpsimd.c:sve_set_vector_length"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490195068,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/process.c:set_tagged_addr_ctrl",
        "arch/arm64/kernel/process.c:arch_dup_task_struct",
        "arch/arm64/kernel/process.c:flush_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490210608,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:sve_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490234520,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm64/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "arch/arm64/kernel/signal.c:restore_fpsimd_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490277676,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm64/kernel/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/syscall.c:el0_svc_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490336228,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm64/kernel/ssbd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490528240,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm64/kvm/fpsimd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_put_fp",
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp",
        "arch/arm64/kvm/fpsimd.c:kvm_arch_vcpu_ctxsync_fp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490630656,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490658908,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490718596,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490748952,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503924060,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491629296,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491669652,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491789720,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492416908,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492484580,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493953316,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493993192,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498810908,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224415356,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm/kernel/elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/elf.c:elf_set_personality"
      ],
      "caller_func": []
    },
    {
      "addr": 3224430468,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/arm/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/signal.c:do_work_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 3224706496,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3224734568,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 3224777220,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 3224798076,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 3236533664,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 3225583296,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 3225623904,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3225737440,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226301888,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 3226357704,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 3227458084,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 3231422044,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282264596,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:ptrace_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282303880,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/process.c:copy_thread_tls",
        "arch/powerpc/kernel/process.c:restore_tm_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282308864,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/powerpc/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/signal.c:do_notify_resume",
        "arch/powerpc/kernel/signal.c:do_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283446756,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283482656,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283535028,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283577488,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297770968,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283797632,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284209792,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284622464,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284677432,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284839424,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285685808,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285770772,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:load_elf_binary",
        "fs/binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:load_elf_binary",
        "fs/compat_binfmt_elf.c:load_elf_binary"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287640108,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292006116,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294887092,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/cpuidle-pseries.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle-pseries.c:snooze_loop",
        "drivers/cpuidle/cpuidle-pseries.c:snooze_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294888828,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/cpuidle-powernv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle-powernv.c:snooze_loop",
        "drivers/cpuidle/cpuidle-powernv.c:snooze_loop"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271344308,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/riscv/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/ptrace.c:ptrace_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271346248,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/riscv/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/signal.c:do_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271384042,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271403650,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271436194,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_request",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271452016,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:signal_setup_done",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279793146,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272027410,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272060906,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272103960,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272549180,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273509956,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276309220,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863653,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040796,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049191,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589802604,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101060,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107400,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115984,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122551,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589803040,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468596,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494181,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579532774,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579564378,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589783453,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738664,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580051932,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580335528,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580372969,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580479249,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028751,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029669,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581085038,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362729,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584910077,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585773981,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589804128,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578857075,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973756,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983088,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589525036,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579033476,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039816,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048080,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054503,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589525456,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397498,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579423036,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461558,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492992,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589505943,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669018,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997244,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580282786,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580320137,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580426385,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974847,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975749,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581032222,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582300429,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584815981,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585633165,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589526490,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863589,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040380,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048775,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590246012,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100612,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106952,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115536,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122103,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590246448,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468516,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494101,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530054,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579561658,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590226861,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579723125,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580043468,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326776,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580364217,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470497,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581019951,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020869,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581076238,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353209,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584911501,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585963021,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590247536,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
  "name": "clear_ti_thread_flag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863909,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/entry/common.c:exit_to_usermode_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044044,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_ia32",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit",
        "arch/x86/kernel/process_64.c:set_personality_64bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579052558,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297100,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:mwait_idle",
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:speculation_ctrl_update_tif",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/process.c:exit_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105108,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpregs_mark_activate",
        "arch/x86/kernel/fpu/core.c:switch_fpu_return"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111980,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579120624,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ptrace.c:set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127223,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:user_disable_single_step",
        "arch/x86/kernel/step.c:enable_step",
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590297600,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579500251,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579526638,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:release_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562710,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:ptrace_resume",
        "kernel/ptrace.c:__ptrace_unlink",
        "kernel/ptrace.c:__ptrace_unlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579595154,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:get_signal",
        "kernel/signal.c:flush_signals"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590277215,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579770485,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/sched/idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/idle.c:do_idle",
        "kernel/sched/idle.c:call_cpuidle",
        "kernel/sched/idle.c:default_idle_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580094236,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381848,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580419619,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580526193,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581081257,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_deny_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082213,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "kernel/user-return-notifier.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581138094,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582430664,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585017581,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_s2idle",
        "drivers/idle/intel_idle.c:intel_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586070760,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590298736,
      "name": "clear_ti_thread_flag",
      "external": false,
      "loc": "include/linux/thread_info.h:58",
      "file": "drivers/cpuidle/poll_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/poll_state.c:poll_idle"
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
void clear_ti_thread_flag(struct thread_info * ti, int flag)
```
</details>
</li>
</ul>

# Function: <code>native_restore_fl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579256240,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:29",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579273158,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:29",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:vsmp_restore_fl",
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_disable",
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256240,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579255296,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:29",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579272452,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:29",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_enable",
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_disable",
        "arch/x86/kernel/vsmp_64.c:vsmp_restore_fl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255296,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579268848,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:33",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579287940,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:33",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_enable",
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_disable",
        "arch/x86/kernel/vsmp_64.c:vsmp_restore_fl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268848,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579265456,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:33",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579284884,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:33",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_enable",
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_disable",
        "arch/x86/kernel/vsmp_64.c:vsmp_restore_fl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265456,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579282288,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:34",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579303460,
      "name": "native_restore_fl",
      "external": false,
      "loc": "arch/x86/include/asm/irqflags.h:34",
      "file": "arch/x86/kernel/vsmp_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_enable",
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_disable",
        "arch/x86/kernel/vsmp_64.c:vsmp_restore_fl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282288,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 8
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579315339,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:37",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_enable",
        "arch/x86/kernel/vsmp_64.c:vsmp_irq_disable",
        "arch/x86/kernel/vsmp_64.c:vsmp_restore_fl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078864,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:37",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083488,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:39",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093152,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:39",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095136,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:39",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107040,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:39",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106592,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:39",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095520,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604572706,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:39",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:kernel_init_freeable",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/pt.c:intel_pt_handle_vmx",
        "arch/x86/events/intel/uncore.c:uncore_pmu_hrtimer",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/dumpstack.c:oops_end",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state",
        "arch/x86/kernel/tsc.c:pit_hpet_ptimer_calibrate_cpu",
        "arch/x86/kernel/tsc.c:set_cyc2ns_scale",
        "arch/x86/kernel/process.c:speculation_ctrl_update",
        "arch/x86/kernel/process.c:set_tsc_mode",
        "arch/x86/kernel/process.c:disable_TSC",
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/mce/core.c:__start_timer",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_bp_pat_init",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi",
        "arch/x86/kernel/smp.c:smp_reboot_interrupt",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/apic.c:enable_IR_x2apic",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown",
        "arch/x86/kernel/apic/apic.c:native_apic_icr_write",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc",
        "arch/x86/kernel/apic/io_apic.c:check_timer",
        "arch/x86/kernel/apic/io_apic.c:timer_irq_works",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/kgdb.c:kgdb_notify",
        "arch/x86/kernel/kvm.c:__send_ipi_mask",
        "arch/x86/kernel/paravirt.c:native_flush_tlb_global",
        "arch/x86/mm/init.c:cr4_set_bits",
        "arch/x86/mm/tlb.c:leave_mm",
        "arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking",
        "arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "kernel/softirq.c:__tasklet_schedule_common",
        "kernel/softirq.c:raise_softirq",
        "kernel/workqueue.c:cancel_delayed_work",
        "kernel/workqueue.c:__cancel_work_timer",
        "kernel/workqueue.c:mod_delayed_work_on",
        "kernel/workqueue.c:queue_delayed_work_on",
        "kernel/workqueue.c:queue_work_node",
        "kernel/workqueue.c:queue_work_on",
        "kernel/kthread.c:kthreadd",
        "kernel/sched/core.c:yield_to",
        "kernel/sched/cputime.c:vtime_init_idle",
        "kernel/sched/fair.c:load_balance",
        "kernel/sched/debug.c:sched_debug_header",
        "kernel/locking/spinlock.c:_raw_write_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_spin_unlock_irqrestore",
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/rcu/tree.c:do_nocb_deferred_wakeup_common",
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:rcu_nocb_cb_kthread",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:nocb_gp_wait",
        "kernel/rcu/tree.c:rcutree_online_cpu",
        "kernel/rcu/tree.c:__call_rcu",
        "kernel/rcu/tree.c:rcu_core",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:rcu_do_batch",
        "kernel/rcu/tree.c:note_gp_changes",
        "kernel/rcu/tree.c:rcu_irq_enter_irqson",
        "kernel/rcu/tree.c:rcu_idle_exit",
        "kernel/rcu/tree.c:rcu_irq_exit_irqson",
        "kernel/time/clockevents.c:clockevents_update_freq",
        "kernel/time/tick-oneshot.c:tick_oneshot_mode_active",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "kernel/time/tick-sched.c:__tick_nohz_task_switch",
        "kernel/smp.c:on_each_cpu_mask",
        "kernel/smp.c:on_each_cpu",
        "kernel/smp.c:generic_exec_single",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/debug_core.c:kgdb_cpu_enter",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/relay.c:relay_late_setup_files",
        "kernel/tsacct.c:acct_update_integrals",
        "kernel/trace/trace_clock.c:trace_clock_global",
        "kernel/trace/ftrace.c:ftrace_init",
        "kernel/trace/ftrace.c:ftrace_process_locs",
        "kernel/trace/ftrace.c:profile_graph_return",
        "kernel/trace/ring_buffer.c:ring_buffer_free_read_page",
        "kernel/trace/ring_buffer.c:ring_buffer_empty",
        "kernel/trace/ring_buffer.c:ring_buffer_consume",
        "kernel/trace/ring_buffer.c:ring_buffer_peek",
        "kernel/trace/ring_buffer.c:rb_get_reader_page",
        "kernel/trace/trace.c:tracing_snapshot_instance_cond",
        "kernel/trace/trace_functions.c:function_stack_trace_call",
        "kernel/trace/trace_sched_wakeup.c:wakeup_reset",
        "kernel/trace/trace_sched_wakeup.c:wakeup_tracer_call",
        "kernel/trace/trace_stack.c:stack_max_size_write",
        "kernel/trace/trace_stack.c:stack_trace_call",
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry",
        "kernel/trace/blktrace.c:__blk_add_trace",
        "kernel/trace/blktrace.c:__trace_note_message",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_unlock",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_pop",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_populate",
        "kernel/bpf/percpu_freelist.c:pcpu_freelist_push",
        "kernel/events/core.c:perf_event_exec",
        "kernel/events/core.c:perf_event_read_local",
        "kernel/events/core.c:perf_lock_task_context",
        "kernel/events/core.c:perf_lock_task_context",
        "kernel/events/core.c:perf_cgroup_switch",
        "mm/filemap.c:filemap_fault",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:wb_writeout_inc",
        "mm/swap.c:lru_add_drain_cpu",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/gup.c:__get_user_pages_fast",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/page_alloc.c:zone_pcp_reset",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:rmqueue",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page_list",
        "mm/page_alloc.c:free_unref_page",
        "mm/page_alloc.c:drain_pages_zone",
        "mm/page_alloc.c:drain_zone_pages",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__slab_free",
        "mm/slub.c:__slab_free",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:put_cpu_partial",
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:refill_stock",
        "mm/memcontrol.c:drain_local_stock",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_write",
        "fs/buffer.c:end_buffer_async_read",
        "fs/buffer.c:end_buffer_async_read",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:__get_reqs_available",
        "fs/aio.c:put_reqs_available",
        "fs/io_uring.c:io_poll_wake",
        "fs/ext4/page-io.c:ext4_finish_bio",
        "security/selinux/avc.c:avc_alloc_node",
        "block/blk-softirq.c:__blk_complete_request",
        "block/blk-softirq.c:trigger_softirq",
        "lib/random32.c:__prandom_reseed",
        "lib/irq_poll.c:irq_poll_complete",
        "drivers/clk/clk.c:clk_enable_lock",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/char/random.c:add_device_randomness",
        "drivers/char/random.c:crng_fast_load",
        "drivers/char/hpet.c:hpet_alloc",
        "drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_dev_parity_test",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags",
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_trylock",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "arch/x86/pci/direct.c:pci_direct_probe",
        "net/core/dev.c:napi_complete_done",
        "net/core/dev.c:__napi_schedule",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:__dev_kfree_skb_irq",
        "net/core/dev.c:__netif_schedule",
        "net/core/netpoll.c:netpoll_send_udp",
        "net/core/netpoll.c:zap_completion_queue",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/tcp_output.c:tcp_wfree",
        "net/ipv4/tcp_output.c:tcp_tasklet_func",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "lib/dump_stack.c:dump_stack",
        "lib/dump_stack.c:dump_stack",
        "lib/flex_proportions.c:fprop_new_period",
        "lib/flex_proportions.c:fprop_new_period"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579027568,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:39",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095072,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
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
void native_restore_fl(long unsigned int flags)
```

```json
{
  "name": "native_restore_fl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "native_restore_fl",
      "external": true,
      "loc": "arch/x86/include/asm/irqflags.h:39",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579099312,
      "name": "native_restore_fl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void native_restore_fl(long unsigned int flags)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void native_restore_fl(long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_restore_fl(long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_restore_fl(long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_restore_fl(long unsigned int flags)
```
</details>
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

# Function: <code>touch_softlockup_watchdog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580133200,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:228",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_nmi_watchdog"
      ],
      "caller_func": [
        "arch/x86/xen/smp.c:cpu_bringup",
        "kernel/panic.c:panic",
        "kernel/sched/clock.c:sched_clock_idle_wakeup_event",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/tick-sched.c:tick_nohz_idle_exit",
        "kernel/time/tick-sched.c:tick_irq_enter",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133200,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580167345,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:246",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:touch_nmi_watchdog"
      ],
      "caller_func": [
        "arch/x86/xen/smp.c:cpu_bringup",
        "kernel/panic.c:panic",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "lib/nmi_backtrace.c:nmi_trigger_all_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167296,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580207760,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:186",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:cpu_bringup",
        "kernel/panic.c:panic",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/watchdog_hld.c:touch_nmi_watchdog",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207760,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580215824,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:269",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580215824,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267168,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:278",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267168,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327600,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:278",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327600,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580380592,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580380592,
      "name": "touch_softlockup_watchdog",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433424,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:280",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433424,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580482176,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:282",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580482176,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580567104,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:261",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:boot_delay_msec",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:__erst_clear_from_storage",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567104,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580554976,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:261",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:boot_delay_msec",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:__erst_clear_from_storage",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554976,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580558144,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558144,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580728096,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580728096,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940448,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt",
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/kernel/kgdb.c:kgdb_nmi_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940448,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233872,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:273",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt",
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/kernel/kgdb.c:kgdb_nmi_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:__erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233872,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328256,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:373",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt",
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/kernel/kgdb.c:kgdb_nmi_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:__erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328256,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434560,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:400",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt",
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/kernel/kgdb.c:kgdb_nmi_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:__erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434560,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491758000,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:282",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "kernel/hung_task.c:watchdog",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491758000,
      "name": "touch_softlockup_watchdog",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:282",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225708456,
      "name": "touch_softlockup_watchdog",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284799312,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:282",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284799312,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:282",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/hung_task.c:watchdog",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272081230,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580450976,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:282",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580450976,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580398048,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:282",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398048,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442224,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:282",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442224,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void touch_softlockup_watchdog()
```

```json
{
  "name": "touch_softlockup_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580497856,
      "name": "touch_softlockup_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:282",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range",
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi",
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/power/snapshot.c:memory_bm_next_pfn",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
        "kernel/time/timekeeping.c:timekeeping_resume",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497856,
      "name": "touch_softlockup_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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

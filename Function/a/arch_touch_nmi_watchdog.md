# Function: <code>arch_touch_nmi_watchdog</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580218720,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:27",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218720,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269584,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269584,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580330016,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580330016,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580383232,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383232,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580436064,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436064,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580484832,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484832,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580569680,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:boot_delay_msec",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
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
      "addr": 18446744071580569680,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557376,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:boot_delay_msec",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
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
      "addr": 18446744071580557376,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560688,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
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
      "addr": 18446744071580560688,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580730720,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/debug.c:sysrq_sched_debug_show",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
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
      "addr": 18446744071580730720,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943408,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1",
        "kernel/hung_task.c:check_hung_task",
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages",
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
      "addr": 18446744071580943408,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237296,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237296,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328224,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:96",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328224,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434528,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:96",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/sched/core.c:show_state_filter",
        "kernel/sched/build_utility.c:sysrq_sched_debug_show",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434528,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282389904,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "arch/powerpc/kernel/watchdog.c:313",
      "file": "arch/powerpc/kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "kernel/panic.c:panic",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282389904,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:113",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580453632,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580453632,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580400704,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580400704,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580444880,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444880,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
void arch_touch_nmi_watchdog()
```

```json
{
  "name": "arch_touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580500512,
      "name": "arch_touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:32",
      "file": "kernel/watchdog_hld.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_sched_clock_irq",
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
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500512,
      "name": "arch_touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void arch_touch_nmi_watchdog()
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void arch_touch_nmi_watchdog()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void arch_touch_nmi_watchdog()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void arch_touch_nmi_watchdog()
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

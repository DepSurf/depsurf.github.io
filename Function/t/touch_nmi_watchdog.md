# Function: <code>touch_nmi_watchdog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void touch_nmi_watchdog()
```

```json
{
  "name": "touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580133232,
      "name": "touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:252",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_stack_log_lvl",
        "arch/x86/kernel/dumpstack.c:print_trace_address",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133232,
      "name": "touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void touch_nmi_watchdog()
```

```json
{
  "name": "touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580167328,
      "name": "touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog.c:268",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack_64.c:show_stack_log_lvl",
        "arch/x86/kernel/dumpstack.c:print_trace_address",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp",
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "kernel/panic.c:panic",
        "kernel/sched/core.c:show_state_filter",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
        "drivers/acpi/osl.c:acpi_os_stall",
        "drivers/acpi/apei/erst.c:erst_timedout",
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580167328,
      "name": "touch_nmi_watchdog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void touch_nmi_watchdog()
```

```json
{
  "name": "touch_nmi_watchdog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580210576,
      "name": "touch_nmi_watchdog",
      "external": true,
      "loc": "kernel/watchdog_hld.c:57",
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
        "kernel/stop_machine.c:multi_cpu_stop",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/hung_task.c:watchdog",
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
      "addr": 18446744071580210576,
      "name": "touch_nmi_watchdog",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579037346,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579039808,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579133066,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579189757,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192533,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251825,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579388186,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579608,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579776896,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915404,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580103162,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580181092,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580210347,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215582,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580328604,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580684890,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584047935,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584328079,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584725854,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:91",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579019250,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579045553,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048000,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579147450,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579183659,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205601,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579208341,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268593,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415513,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535435,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579608944,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579808832,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579960812,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580156351,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580232669,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580261689,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580266926,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381728,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580768257,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584311967,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584732399,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585140238,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579022215,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579024899,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579050493,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053532,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579157104,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579195527,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217062,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220405,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279806,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429721,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579567474,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579643795,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579846588,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912804,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580007445,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215766,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293168,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322152,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580327298,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580444329,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580904560,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584532143,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584961059,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585374318,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:124",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579025275,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579027965,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029004,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055298,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579057506,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579146592,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579184935,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579240742,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244083,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303758,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463417,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579604658,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579681349,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579893580,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976221,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580054469,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580268470,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580345952,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580374943,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580380298,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580500009,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580979216,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584629471,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585065427,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585498030,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579033663,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579035485,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579036234,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579063093,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066165,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579159769,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579197658,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255746,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258147,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320398,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579481226,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579628291,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715150,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579928313,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580016431,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580098055,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580319675,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580398577,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580427526,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580433018,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580556554,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581401983,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584829151,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269622,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585716302,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579035983,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037805,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038554,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065189,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068245,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579162233,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579198741,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257410,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259795,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324430,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474197,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507126,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579654138,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579757597,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579978457,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067069,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580147031,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368508,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447361,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580476278,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580481770,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580604144,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581462975,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584964879,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585407574,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585856926,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579045547,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047605,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048058,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579073507,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075628,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579180580,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579219693,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579284428,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286771,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353629,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496594,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535311,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685431,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579791006,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579925466,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sysrq_sched_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580025613,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:boot_delay_msec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580125129,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580209932,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_active_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580442208,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580528975,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580561088,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580565880,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702494,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581668243,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585660431,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586119289,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:__erst_clear_from_storage",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586591300,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579048987,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579050949,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579051386,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591245733,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591246338,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579176772,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579214141,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291704,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293139,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353357,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479068,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591277447,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591280792,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579777265,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919338,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sysrq_sched_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580005066,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:boot_delay_msec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591305387,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580194028,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_active_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580430272,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580517087,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549186,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553944,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591320123,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581715929,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585786047,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586239065,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:__erst_clear_from_storage",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586701988,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579051824,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053870,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055658,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056576,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579058716,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591189527,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591190132,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579183402,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579216605,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579294407,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295811,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579357888,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480939,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591220345,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591223741,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579785857,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579927594,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sysrq_sched_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006386,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580091498,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199356,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580434368,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580520751,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580552324,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580557112,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591262421,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581736132,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585666415,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586113840,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586585142,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579072706,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074780,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076547,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078220,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579079866,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592053089,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592053694,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579217642,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579254813,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579341524,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342947,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417568,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579546845,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592098880,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592104826,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579880254,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580050842,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/debug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/debug.c:sysrq_sched_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580139317,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580229486,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580346076,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580599152,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692239,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722081,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580727002,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592171522,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582012475,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586145887,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586613776,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587125910,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579097847,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100017,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101783,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104115,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106292,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579108157,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593819840,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593820680,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594662256,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402522,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403759,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579485280,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/kernel/kgdb.c:kgdb_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635980,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593866229,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579848234,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997294,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580183736,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sysrq_sched_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580282215,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593917231,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559756,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580802447,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903183,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580934190,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939231,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593945090,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582439116,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587378326,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587877506,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588433511,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579134238,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136565,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138565,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141297,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142946,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579145637,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579179092,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183099,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596396692,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579482793,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579484322,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578704,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/kernel/kgdb.c:kgdb_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579753120,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805085,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579988855,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580159318,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580370567,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sysrq_sched_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580490951,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634153,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819180,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087855,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194559,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227127,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232593,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410819,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582947964,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588628150,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589224477,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:__erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589861287,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:134",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579134772,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137461,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139322,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142237,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143572,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579146241,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579182525,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186523,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596927652,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579496450,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579591248,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/kernel/kgdb.c:kgdb_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579799434,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579853323,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580042041,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580207734,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580439191,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sysrq_sched_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580511015,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580562791,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714011,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580902476,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179647,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581288806,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321479,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326927,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505795,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588915910,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589521053,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:__erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590170007,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579161387,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163923,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165705,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/irqdomain.c:hv_map_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171103,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579172894,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579175872,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579211741,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215739,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597853380,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_timed_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579526274,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579621008,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify",
        "arch/x86/kernel/kgdb.c:kgdb_nmi_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579832778,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890983,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580084793,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580256054,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580498423,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sysrq_sched_debug_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580571009,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580623637,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580787300,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:print_other_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993004,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581285327,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394902,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_getchar"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581427783,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt",
        "kernel/debug/kdb/kdb_bt.c:kdb_bt1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433232,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:check_hung_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617282,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589211974,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589828996,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:__erst_read",
        "drivers/acpi/apei/erst.c:erst_write",
        "drivers/acpi/apei/erst.c:erst_exec_stall_while_true"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590510210,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:139",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_lsr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490642360,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490820604,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490935884,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491162368,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491281704,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491367328,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_active_timers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491632228,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491717420,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491751624,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491757524,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491901948,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497379884,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497680880,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498590132,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224718288,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 3224853960,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 3224954408,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225189788,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 3225288424,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 3225366904,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 3225585516,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 3225670648,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3225699632,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 3225705932,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 3225844396,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226670380,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3231223152,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283280792,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283460776,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283654200,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283791780,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284061980,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284186044,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284303664,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284625432,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284743004,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284789796,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284798860,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284990036,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291812664,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271394682,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271494780,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271568676,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271717012,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271798882,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271857754,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272029282,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272078820,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272189884,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276189062,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579036335,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038157,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038906,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065541,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068597,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579162585,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579197589,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256114,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258499,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320334,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480790,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579630442,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579733517,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579947193,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580035805,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580116231,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580337308,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416161,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580445078,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450570,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580572944,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581431823,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584915055,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585617934,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578968972,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970949,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578971715,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998293,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001333,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579093545,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579132581,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191326,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193683,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254878,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409680,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579558794,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579662360,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885177,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579981206,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580061527,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580284549,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580363229,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392150,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397642,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519579,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581374255,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584820975,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585130086,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585482990,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579035919,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037741,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038490,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065125,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068181,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579162153,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579198661,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257314,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259699,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320254,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579480710,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579627722,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717965,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938729,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580027341,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107303,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580328556,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580407409,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580436326,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580441818,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580564192,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581423023,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584916463,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585357974,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585807326,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
  "name": "touch_nmi_watchdog",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579039512,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others",
        "arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041357,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/nested.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/nested.c:hyperv_flush_guest_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042138,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:__send_ipi_mask_ex"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069189,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl",
        "arch/x86/kernel/dumpstack.c:show_trace_log_lvl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072277,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579167337,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579203941,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:__wait_for_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262914,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_cpu_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265299,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:check_tsc_warp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328542,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/kernel/kgdb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kgdb.c:__kgdb_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479525,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "arch/x86/platform/uv/uv_nmi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579512573,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579661365,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765249,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:show_state_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579984969,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/printk/printk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580077218,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_sched_clock_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580159047,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/time/timer_list.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer_list.c:print_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580383676,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:multi_cpu_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580462993,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:vkdb_printf",
        "kernel/debug/kdb/kdb_io.c:kdb_input_flush",
        "kernel/debug/kdb/kdb_io.c:kdb_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491958,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/debug/kdb/kdb_bt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_bt.c:kdb_bt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580497433,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/hung_task.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/hung_task.c:watchdog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580620912,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581487471,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:mark_free_pages",
        "mm/page_alloc.c:mark_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585022543,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_stall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585465254,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/acpi/apei/erst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/erst.c:erst_timedout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585914990,
      "name": "touch_nmi_watchdog",
      "external": false,
      "loc": "include/linux/nmi.h:132",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:serial8250_console_write",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr",
        "drivers/tty/serial/8250/8250_port.c:wait_for_xmitr"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void touch_nmi_watchdog()
```
</details>
</li>
</ul>

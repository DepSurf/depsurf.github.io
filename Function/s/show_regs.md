# Function: <code>show_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579047392,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:300",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/doublefault.c:df_debug",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/watchdog.c:watchdog_timer_fn",
        "lib/bug.c:report_bug",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047392,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579043584,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:308",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/watchdog.c:watchdog_timer_fn",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579043584,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579042672,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:139",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/watchdog.c:watchdog_timer_fn",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579042672,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579035072,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:140",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579035072,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579042912,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack_64.c:153",
      "file": "arch/x86/kernel/dumpstack_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579042912,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:417",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die",
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/kprobes/core.c:longjmp_break_handler",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050774,
      "name": "show_regs.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579049328,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579055579,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:408",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055579,
      "name": "show_regs.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579054304,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579063307,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:408",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063307,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579062080,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579065403,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:413",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065403,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579064176,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579072101,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:445",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:__die_body"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073684,
      "name": "show_regs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579073910,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579072416,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579076335,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:462",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:__die_body"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591245913,
      "name": "show_regs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071591246139,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579076640,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579083279,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:462",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:__die_body"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591189707,
      "name": "show_regs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071591189933,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579083584,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579106239,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:462",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:__die_body"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/kfence/report.c:kfence_report_error",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592053269,
      "name": "show_regs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071592053495,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579106544,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579136846,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:456",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:__die_body"
      ],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die_body",
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/kfence/report.c:kfence_report_error",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593820062,
      "name": "show_regs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071593820329,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579137200,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579180032,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:462",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die_addr",
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "mm/kfence/report.c:kfence_report_error",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180032,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183424,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:465",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die_addr",
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_hardlockup_check",
        "mm/kfence/report.c:kfence_report_error",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183424,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579212640,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:465",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die_addr",
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/sched/core.c:dump_cpu_task",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog.c:watchdog_hardlockup_check",
        "mm/kfence/report.c:kfence_report_error",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212640,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490193136,
      "name": "show_regs",
      "external": true,
      "loc": "arch/arm64/kernel/process.c:291",
      "file": "arch/arm64/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/traps.c:die",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490193136,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224416800,
      "name": "show_regs",
      "external": true,
      "loc": "arch/arm/kernel/process.c:186",
      "file": "arch/arm/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/alignment.c:do_alignment_ldmstm",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224416800,
      "name": "show_regs",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282307108,
      "name": "show_regs",
      "external": true,
      "loc": "arch/powerpc/kernel/process.c:1388",
      "file": "arch/powerpc/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/traps.c:StackOverflow",
        "arch/powerpc/kernel/traps.c:__die",
        "arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt",
        "arch/powerpc/kernel/watchdog.c:wd_smp_clear_cpu_pending",
        "arch/powerpc/kernel/watchdog.c:wd_lockup_ipi",
        "arch/powerpc/platforms/powernv/opal.c:pnv_platform_error_reboot",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282307108,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271341610,
      "name": "show_regs",
      "external": true,
      "loc": "arch/riscv/kernel/process.c:34",
      "file": "arch/riscv/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/traps.c:do_trap",
        "arch/riscv/kernel/traps.c:die",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/watchdog.c:watchdog_timer_fn",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/sysrq.c:sysrq_handle_showallcpus",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271341610,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579065755,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:413",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065755,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579064528,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578998507,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:413",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998507,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071578997280,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579065339,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:413",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065339,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579064112,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void show_regs(struct pt_regs * regs)
```

```json
{
  "name": "show_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579069403,
      "name": "show_regs",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:413",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:__die",
        "arch/x86/kernel/doublefault.c:df_debug",
        "arch/x86/mm/extable.c:early_fixup_exception",
        "arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state_cpu",
        "kernel/panic.c:__warn",
        "kernel/signal.c:get_signal",
        "kernel/debug/kdb/kdb_main.c:kdb_ef",
        "kernel/watchdog.c:watchdog_timer_fn",
        "kernel/watchdog_hld.c:watchdog_overflow_callback",
        "drivers/tty/sysrq.c:sysrq_handle_showregs",
        "drivers/tty/vt/keyboard.c:fn_show_ptregs",
        "lib/nmi_backtrace.c:nmi_cpu_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069403,
      "name": "show_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579068176,
      "name": "show_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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

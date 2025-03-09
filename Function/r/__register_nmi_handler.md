# Function: <code>__register_nmi_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579051104,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:151",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/hw_nmi.c:register_trigger_all_cpu_backtrace",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051104,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579047312,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:154",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/hw_nmi.c:register_trigger_all_cpu_backtrace",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047312,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579046368,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:154",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579046368,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579038912,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:156",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579038912,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579047104,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:156",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047104,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579051024,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:156",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579051024,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579055824,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:156",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/smpboot.c:native_cpu_up",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055824,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064464,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:159",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064464,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066288,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:159",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066288,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579074512,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:155",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579074512,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077392,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:155",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077392,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579084320,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:155",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579084320,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579107280,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:155",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107280,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579137696,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:155",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137696,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181264,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:155",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181264,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579184688,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:164",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184688,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213904,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:165",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:perf_event_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smp.c:native_stop_other_cpus",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213904,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066640,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:159",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066640,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578999392,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:159",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999392,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579066224,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:159",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066224,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```

```json
{
  "name": "__register_nmi_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579070288,
      "name": "__register_nmi_handler",
      "external": true,
      "loc": "arch/x86/kernel/nmi.c:159",
      "file": "arch/x86/kernel/nmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/reboot.c:nmi_shootdown_cpus",
        "arch/x86/kernel/smpboot.c:do_boot_cpu",
        "arch/x86/kernel/apic/hw_nmi.c:register_nmi_cpu_backtrace_handler",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "arch/x86/platform/uv/uv_nmi.c:uv_register_nmi_notifier",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579070288,
      "name": "__register_nmi_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __register_nmi_handler(unsigned int type, struct nmiaction * action)
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

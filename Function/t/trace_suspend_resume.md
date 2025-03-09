# Function: <code>trace_suspend_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579376609,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687929,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579689312,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:pm_suspend"
      ],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend"
      ]
    },
    {
      "addr": 18446744071579693856,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ]
    },
    {
      "addr": 18446744071579880446,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_unfreeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583545675,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ]
    },
    {
      "addr": 18446744071584400012,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584456301,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579689312,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071579693856,
      "name": "trace_suspend_resume.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071583545675,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579389734,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:disable_nonboot_cpus",
        "kernel/cpu.c:disable_nonboot_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579707195,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710753,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    },
    {
      "addr": 18446744071579712960,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ]
    },
    {
      "addr": 18446744071579910193,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583866734,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ]
    },
    {
      "addr": 18446744071584735356,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584797705,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:195",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579708608,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071579712960,
      "name": "trace_suspend_resume.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071583866734,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579410114,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734763,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738289,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    },
    {
      "addr": 18446744071579740496,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ]
    },
    {
      "addr": 18446744071579940658,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005833,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ]
    },
    {
      "addr": 18446744071584925228,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584989641,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736144,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071579740496,
      "name": "trace_suspend_resume.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071584005833,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579397505,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730649,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579734416,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": [
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend",
        "kernel/power/suspend.c:pm_suspend"
      ]
    },
    {
      "addr": 18446744071579736624,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ]
    },
    {
      "addr": 18446744071579948578,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584057363,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585010124,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585074505,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:200",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732016,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071579736624,
      "name": "trace_suspend_resume.constprop.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579425563,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579763657,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579766291,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579771024,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579994274,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584325363,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585432300,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585497753,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765024,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579441135,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579797864,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579800840,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579804561,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580046412,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584545954,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585675445,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585741973,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:201",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433072,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071579799344,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579474639,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579844472,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579847464,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851201,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093244,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584643170,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585805701,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585874709,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579466608,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 18446744071579845968,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579492558,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579878264,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882064,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885525,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137103,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584843346,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586038933,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586111925,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484480,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071579880128,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579518521,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579928472,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579932272,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579935749,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185248,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584979138,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586186533,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586259349,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579510464,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071579930288,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579547969,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071579972504,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976352,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/power/suspend.c:s2idle_enter"
      ],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_prepare",
        "kernel/power/suspend.c:suspend_prepare"
      ]
    },
    {
      "addr": 18446744071579979323,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580250405,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585675107,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586948629,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587027781,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539024,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071579974208,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591278015,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071579960296,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579963144,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/power/suspend.c:s2idle_enter"
      ],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_prepare",
        "kernel/power/suspend.c:suspend_prepare"
      ]
    },
    {
      "addr": 18446744071579965507,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234250,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585797774,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587033845,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587112110,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521184,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579961136,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591220913,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071579962920,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579965800,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state"
      ]
    },
    {
      "addr": 18446744071579968147,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580239370,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585678606,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586917637,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586998414,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524128,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071579963760,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592099826,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071580092680,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580095698,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580099267,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388906,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586158510,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587480005,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587564608,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596208,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593867374,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus"
      ]
    },
    {
      "addr": 18446744071580230008,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580233472,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580237742,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606726,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587392375,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588800453,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588898480,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579688672,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579822069,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580422608,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580426984,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580432129,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870589,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588645358,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590296995,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590409146,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
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
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579871189,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580491984,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580496328,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501361,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954349,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588933230,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590617059,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590728714,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
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
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579909109,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:thaw_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551872,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580556216,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:enter_state",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580561249,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045933,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589229838,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590976163,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591090634,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:248",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_noirq_suspend_devices",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_noirq_resume_devices",
        "drivers/base/power/main.c:dpm_noirq_resume_devices"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490654656,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446603336491138384,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491142800,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491410152,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498984948,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499080160,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490647432,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 18446603336491140144,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224731152,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 3225135608,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 3225138776,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225143764,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 3225405872,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 3231553520,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 3231633256,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224722340,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    },
    {
      "addr": 3225137276,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283477428,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 13835058055284031160,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284035448,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284356904,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292137208,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292260676,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283466304,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 13835058055284033216,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "trace_suspend_resume",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271701972,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579492185,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579900120,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579903579,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585946901,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586022677,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484128,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579421049,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579835544,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579838826,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579842793,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580100160,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584832557,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585795989,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585868661,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413008,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071579837360,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579492105,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579888744,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579892544,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579896021,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145520,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584930722,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586136549,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586209365,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484048,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071579890560,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```

```json
{
  "name": "trace_suspend_resume",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579524622,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/cpu.c:freeze_secondary_cpus"
      ],
      "caller_func": [
        "kernel/cpu.c:enable_nonboot_cpus",
        "kernel/cpu.c:enable_nonboot_cpus"
      ]
    },
    {
      "addr": 18446744071579934520,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:thaw_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938480,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579942005,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197486,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "kernel/time/tick-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_unfreeze",
        "kernel/time/tick-common.c:tick_freeze",
        "kernel/time/tick-common.c:tick_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585036866,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586245141,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/syscore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_resume",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/syscore.c:syscore_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586318373,
      "name": "trace_suspend_resume",
      "external": false,
      "loc": "include/trace/events/power.h:226",
      "file": "drivers/base/power/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_late",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_suspend_noirq",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_complete",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_early",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq",
        "drivers/base/power/main.c:dpm_resume_noirq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515792,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071579936384,
      "name": "trace_suspend_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void trace_suspend_resume(const char * action, int val, bool start)
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

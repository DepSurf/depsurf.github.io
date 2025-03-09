# Function: <code>register_pm_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683888,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:29",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/firmware_class.c:firmware_class_init",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683888,
      "name": "register_pm_notifier",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579702992,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:29",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579702992,
      "name": "register_pm_notifier",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579730224,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:29",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579730224,
      "name": "register_pm_notifier",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726192,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:29",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726192,
      "name": "register_pm_notifier",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579758864,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:29",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_class.c:firmware_class_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579758864,
      "name": "register_pm_notifier",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579793328,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:58",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793328,
      "name": "register_pm_notifier",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579839920,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:58",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579839920,
      "name": "register_pm_notifier",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873920,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:70",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873920,
      "name": "register_pm_notifier",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579923504,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579923504,
      "name": "register_pm_notifier",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579967280,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967280,
      "name": "register_pm_notifier",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955200,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955200,
      "name": "register_pm_notifier",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579957920,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957920,
      "name": "register_pm_notifier",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580087280,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087280,
      "name": "register_pm_notifier",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224080,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/char/random.c:random_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224080,
      "name": "register_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580415120,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:74",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580415120,
      "name": "register_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580484000,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:102",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484000,
      "name": "register_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580543840,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:86",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/char/random.c:random_init",
        "drivers/char/random.c:random_init",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/watchdog/watchdog_core.c:__watchdog_register_device",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580543840,
      "name": "register_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491131800,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491131800,
      "name": "register_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225129352,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "sound/soc/soc-jack.c:snd_soc_jack_add_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225129352,
      "name": "register_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284022512,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/mfd/twl6030-irq.c:twl6030_init_irq",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284022512,
      "name": "register_pm_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
  "name": "register_pm_notifier",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "register_pm_notifier",
      "external": false,
      "loc": "include/linux/suspend.h:512",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "register_pm_notifier",
      "external": false,
      "loc": "include/linux/suspend.h:512",
      "file": "drivers/mfd/twl6030-irq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "register_pm_notifier",
      "external": false,
      "loc": "include/linux/suspend.h:512",
      "file": "drivers/thermal/thermal_core.c",
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
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895616,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/xen/manage.c:xen_setup_pm_notifier",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895616,
      "name": "register_pm_notifier",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579830576,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579830576,
      "name": "register_pm_notifier",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883776,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883776,
      "name": "register_pm_notifier",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
```

```json
{
  "name": "register_pm_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579929536,
      "name": "register_pm_notifier",
      "external": true,
      "loc": "kernel/power/main.c:71",
      "file": "kernel/power/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:cpu_hotplug_pm_sync_init",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/fgraph.c:register_ftrace_graph",
        "drivers/acpi/battery.c:acpi_battery_add",
        "drivers/base/power/trace.c:early_resume_init",
        "drivers/base/firmware_loader/main.c:firmware_class_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "drivers/mmc/core/core.c:mmc_register_pm_notifier",
        "arch/x86/power/cpu.c:bsp_pm_check_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929536,
      "name": "register_pm_notifier",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int register_pm_notifier(struct notifier_block * nb)
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

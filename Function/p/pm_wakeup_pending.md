# Function: <code>pm_wakeup_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584466560,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:841",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend_noirq",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466560,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584803136,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:839",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584803136,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584995136,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:839",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584995136,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585080176,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:840",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585080176,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585503504,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:841",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585503504,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585748304,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:840",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585748304,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585881024,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:846",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585881024,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586118144,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:830",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late",
        "drivers/base/power/main.c:__device_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118144,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586265632,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:850",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586265632,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587034336,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:909",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:create_image",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587034336,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587117792,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:909",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:create_image",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587117792,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587004192,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:910",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:create_image",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004192,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:911",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:create_image",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592492828,
      "name": "pm_wakeup_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071587570496,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:911",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:create_image",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594362779,
      "name": "pm_wakeup_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071588901584,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:881",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:create_image",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596247375,
      "name": "pm_wakeup_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071590412464,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:876",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:create_image",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596775728,
      "name": "pm_wakeup_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071590732032,
      "name": "pm_wakeup_pending",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:876",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:create_image",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597684978,
      "name": "pm_wakeup_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071591093952,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499089232,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:850",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "kernel/power/suspend.c:s2idle_loop",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499089232,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231641052,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:850",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231641052,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292271152,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:850",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292271152,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_wakeup_pending",
      "external": false,
      "loc": "include/linux/suspend.h:526",
      "file": "kernel/power/process.c",
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028880,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:850",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028880,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585874896,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:850",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585874896,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586215648,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:850",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586215648,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool pm_wakeup_pending()
```

```json
{
  "name": "pm_wakeup_pending",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586324752,
      "name": "pm_wakeup_pending",
      "external": true,
      "loc": "drivers/base/power/wakeup.c:850",
      "file": "drivers/base/power/wakeup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:freeze_secondary_cpus",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "drivers/base/syscore.c:syscore_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend_late"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586324752,
      "name": "pm_wakeup_pending",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
bool pm_wakeup_pending()
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

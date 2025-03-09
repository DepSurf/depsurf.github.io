# Function: <code>__clocksource_register_scale</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860512,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:728",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860512,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579890000,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:760",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890000,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579901888,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:770",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901888,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910448,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:777",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910448,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955632,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:776",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955632,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580003200,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:798",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580003200,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580050512,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:918",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050512,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094064,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:918",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094064,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143024,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143024,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_tsc_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207867,
      "name": "__clocksource_register_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580205984,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:917",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591311922,
      "name": "__clocksource_register_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580190720,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:1018",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591254353,
      "name": "__clocksource_register_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580196080,
      "name": "__clocksource_register_scale",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:1150",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592155164,
      "name": "__clocksource_register_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580341696,
      "name": "__clocksource_register_scale",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:1156",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593930185,
      "name": "__clocksource_register_scale.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071580554896,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580812208,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:1175",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580812208,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895408,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:1186",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895408,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580985840,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:1209",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580985840,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491364008,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/mmio.c:clocksource_mmio_init",
        "drivers/clocksource/timer-sprd.c:sprd_suspend_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491364008,
      "name": "__clocksource_register_scale",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225363792,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/timer.c:__omap_sync32k_timer_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/sh_cmt.c:sh_cmt_setup",
        "drivers/clocksource/sh_tmu.c:sh_tmu_setup",
        "drivers/clocksource/em_sti.c:em_sti_probe",
        "drivers/clocksource/mmio.c:clocksource_mmio_init",
        "drivers/clocksource/dw_apb_timer.c:dw_apb_clocksource_register",
        "drivers/clocksource/timer-tegra.c:tegra20_init_rtc",
        "drivers/clocksource/exynos_mct.c:mct_init_dt",
        "drivers/clocksource/timer-qcom.c:msm_dt_timer_init",
        "drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init",
        "drivers/clocksource/timer-rda.c:rda_timer_init",
        "drivers/clocksource/arm_arch_timer.c:arch_timer_common_init",
        "drivers/clocksource/arm_global_timer.c:global_timer_of_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225363792,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284299712,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/time.c:time_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284299712,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271855436,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/timer-riscv.c:riscv_timer_init_dt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271855436,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112224,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112224,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057536,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057536,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580103296,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580103296,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int __clocksource_register_scale(struct clocksource * cs, u32 scale, u32 freq)
```

```json
{
  "name": "__clocksource_register_scale",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580155040,
      "name": "__clocksource_register_scale",
      "external": true,
      "loc": "kernel/time/clocksource.c:925",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_enable",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock",
        "kernel/time/jiffies.c:register_refined_jiffies",
        "kernel/time/jiffies.c:init_jiffies_clocksource",
        "drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource",
        "drivers/clocksource/numachip.c:numachip_timer_init",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155040,
      "name": "__clocksource_register_scale",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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

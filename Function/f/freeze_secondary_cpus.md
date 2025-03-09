# Function: <code>freeze_secondary_cpus</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579409440,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:985",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409440,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396832,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:897",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396832,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424912,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1081",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424912,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1171",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441012,
      "name": "freeze_secondary_cpus.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071579440160,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1188",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474516,
      "name": "freeze_secondary_cpus.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071579473664,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1200",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492428,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071579490896,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1215",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518385,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071579516832,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1346",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547833,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071579546128,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1350",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591277866,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    },
    {
      "addr": 18446744071579527840,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1454",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591220764,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    },
    {
      "addr": 18446744071579532112,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1484",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592099677,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    },
    {
      "addr": 18446744071579604400,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1496",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593867210,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071579697120,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821200,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1520",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821200,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870320,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1880",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870320,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908240,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1925",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908240,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490654408,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1215",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/process.c:machine_shutdown",
        "kernel/power/suspend.c:suspend_enter",
        "drivers/power/reset/sc27xx-poweroff.c:sc27xx_poweroff_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490654408,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224730864,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1215",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/reboot.c:machine_shutdown",
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224730864,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283477152,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1215",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283477152,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1215",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492049,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071579490496,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1215",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420913,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071579419360,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1215",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491969,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071579490416,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int freeze_secondary_cpus(int primary)
```

```json
{
  "name": "freeze_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "freeze_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1215",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/kexec_core.c:kernel_kexec",
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524465,
      "name": "freeze_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
    },
    {
      "addr": 18446744071579522816,
      "name": "freeze_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int freeze_secondary_cpus(int primary)
```
</details>
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
int freeze_secondary_cpus(int primary)
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

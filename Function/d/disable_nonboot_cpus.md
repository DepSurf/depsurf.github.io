# Function: <code>disable_nonboot_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int disable_nonboot_cpus()
```

```json
{
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376448,
      "name": "disable_nonboot_cpus",
      "external": true,
      "loc": "kernel/cpu.c:572",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter",
        "kernel/power/hibernate.c:hibernation_snapshot",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376448,
      "name": "disable_nonboot_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
int disable_nonboot_cpus()
```

```json
{
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579389072,
      "name": "disable_nonboot_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1027",
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
      "addr": 18446744071579389072,
      "name": "disable_nonboot_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_nonboot_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579737437,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:123",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579743365,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:123",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580011850,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:123",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586764118,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:123",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_nonboot_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579733503,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739543,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580019064,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586887398,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:131",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
  "name": "disable_nonboot_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579765993,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579772738,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580066008,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376214,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:129",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
  "name": "disable_nonboot_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579800291,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579806316,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123134,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679918,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:133",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
  "name": "disable_nonboot_cpus",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579846915,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "kernel/power/suspend.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579852956,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "kernel/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable",
        "kernel/power/hibernate.c:hibernation_snapshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580170270,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kernel_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587811006,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588116581,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:137",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588322213,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:142",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490192904,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:142",
      "file": "arch/arm64/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/process.c:machine_shutdown"
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
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224425232,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:142",
      "file": "arch/arm/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/reboot.c:machine_shutdown"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587925861,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:142",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587642325,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:142",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588259269,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:142",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
  "name": "disable_nonboot_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588394789,
      "name": "disable_nonboot_cpus",
      "external": false,
      "loc": "include/linux/cpu.h:142",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable"
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int disable_nonboot_cpus()
```
</details>
</li>
</ul>

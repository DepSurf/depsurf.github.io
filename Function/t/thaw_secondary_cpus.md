# Function: <code>thaw_secondary_cpus</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void thaw_secondary_cpus()
```

```json
{
  "name": "thaw_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1412",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548187,
      "name": "thaw_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071579546352,
      "name": "thaw_secondary_cpus",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void thaw_secondary_cpus()
```

```json
{
  "name": "thaw_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1416",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591278173,
      "name": "thaw_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071579528048,
      "name": "thaw_secondary_cpus",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void thaw_secondary_cpus()
```

```json
{
  "name": "thaw_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1520",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591221071,
      "name": "thaw_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071579532336,
      "name": "thaw_secondary_cpus",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void thaw_secondary_cpus()
```

```json
{
  "name": "thaw_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1550",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:hibernation_restore",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592099984,
      "name": "thaw_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071579604624,
      "name": "thaw_secondary_cpus",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void thaw_secondary_cpus()
```

```json
{
  "name": "thaw_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "thaw_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1562",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593867572,
      "name": "thaw_secondary_cpus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071579697328,
      "name": "thaw_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void thaw_secondary_cpus()
```

```json
{
  "name": "thaw_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821888,
      "name": "thaw_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1586",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821888,
      "name": "thaw_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void thaw_secondary_cpus()
```

```json
{
  "name": "thaw_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871008,
      "name": "thaw_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1946",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871008,
      "name": "thaw_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void thaw_secondary_cpus()
```

```json
{
  "name": "thaw_secondary_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908928,
      "name": "thaw_secondary_cpus",
      "external": true,
      "loc": "kernel/cpu.c:1991",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter",
        "kernel/power/hibernate.c:hibernation_platform_enter",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:resume_target_kernel",
        "kernel/power/hibernate.c:create_image",
        "kernel/power/hibernate.c:create_image",
        "kernel/kexec_core.c:kernel_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908928,
      "name": "thaw_secondary_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void thaw_secondary_cpus()
```
</details>
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

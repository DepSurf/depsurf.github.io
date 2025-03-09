# Function: <code>xen_setup_runstate_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578990864,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "arch/x86/xen/time.c:104",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578990864,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584186480,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:91",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584186480,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584368000,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:91",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_start_kernel",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/suspend.c:xen_arch_post_suspend",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584368000,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584449552,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:91",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584449552,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584860096,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584860096,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585091104,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585091104,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585201280,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201280,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585413808,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413808,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554528,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554528,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586273184,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586273184,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586390384,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390384,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586274368,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:161",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274368,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586786912,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:161",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586786912,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588067232,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:161",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588067232,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589448496,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:161",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589448496,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589748016,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:161",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589748016,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086032,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:161",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086032,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498215880,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/xen/enlighten.c:xen_starting_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498215880,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585316240,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:186",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585316240,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585504928,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585504928,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void xen_setup_runstate_info(int cpu)
```

```json
{
  "name": "xen_setup_runstate_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585612912,
      "name": "xen_setup_runstate_info",
      "external": true,
      "loc": "drivers/xen/time.c:160",
      "file": "drivers/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/time.c:xen_hvm_setup_cpu_clockevents",
        "arch/x86/xen/time.c:xen_time_init",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585612912,
      "name": "xen_setup_runstate_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_setup_runstate_info(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_setup_runstate_info(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_setup_runstate_info(int cpu)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xen_setup_runstate_info(int cpu)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

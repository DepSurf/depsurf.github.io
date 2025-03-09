# Function: <code>switch_to_new_gdt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108400,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:386",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_setup_gdt",
        "arch/x86/xen/enlighten.c:xen_setup_gdt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108400,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579107968,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:450",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_setup_gdt",
        "arch/x86/xen/enlighten.c:xen_setup_gdt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107968,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579106496,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:453",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_setup_gdt",
        "arch/x86/xen/enlighten.c:xen_setup_gdt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579106496,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098160,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:500",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098160,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579113247,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:539",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579109312,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579119599,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:549",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579115536,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579125335,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:549",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121200,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579134981,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:613",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579130768,
      "name": "switch_to_new_gdt",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579136901,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:613",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132656,
      "name": "switch_to_new_gdt",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579152726,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:618",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148960,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579150375,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:636",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146048,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156720,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:634",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152064,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579186250,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:637",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180944,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579233998,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:745",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228432,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579137285,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:613",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133040,
      "name": "switch_to_new_gdt",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068020,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:613",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064176,
      "name": "switch_to_new_gdt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579136837,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:613",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132592,
      "name": "switch_to_new_gdt",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void switch_to_new_gdt(int cpu)
```

```json
{
  "name": "switch_to_new_gdt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579141957,
      "name": "switch_to_new_gdt",
      "external": true,
      "loc": "arch/x86/kernel/cpu/common.c:613",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu",
        "arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579137712,
      "name": "switch_to_new_gdt",
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void switch_to_new_gdt(int cpu)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void switch_to_new_gdt(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void switch_to_new_gdt(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void switch_to_new_gdt(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void switch_to_new_gdt(int cpu)
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

# Function: <code>xen_vcpu_info_reset</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578950037,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:174",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578949856,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578952309,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:178",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578952128,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578954837,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:186",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578954656,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578956837,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:188",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578956656,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578963781,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:188",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578963600,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578966213,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:188",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966032,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578975360,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:188",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975360,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578978080,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:188",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978080,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578987200,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:188",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578987200,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579003232,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:192",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579003232,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579020064,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:146",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579020064,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579047760,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:146",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047760,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579047760,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:146",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579047760,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073088,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:149",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten.c:xen_vcpu_restore",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073088,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578966213,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:188",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966032,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578966149,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:188",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965968,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void xen_vcpu_info_reset(int cpu)
```

```json
{
  "name": "xen_vcpu_info_reset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578966741,
      "name": "xen_vcpu_info_reset",
      "external": true,
      "loc": "arch/x86/xen/enlighten.c:188",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_vcpu_setup",
        "arch/x86/xen/enlighten.c:xen_vcpu_restore"
      ],
      "caller_func": [
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_init_mem_mapping",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_pv_init_platform",
        "arch/x86/xen/smp.c:xen_smp_cpus_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966560,
      "name": "xen_vcpu_info_reset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void xen_vcpu_info_reset(int cpu)
```
</details>
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
void xen_vcpu_info_reset(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_vcpu_info_reset(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_vcpu_info_reset(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_vcpu_info_reset(int cpu)
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
void xen_vcpu_info_reset(int cpu)
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

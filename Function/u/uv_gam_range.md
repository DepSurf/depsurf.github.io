# Function: <code>uv_gam_range</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```

```json
{
  "name": "uv_gam_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579294077,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:454",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579460278,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:454",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_soc_phys_ram_to_gpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294077,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579455200,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071579466894,
      "name": "uv_gam_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```

```json
{
  "name": "uv_gam_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579323743,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:400",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579482371,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:400",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:uv_gpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323743,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579476544,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579488160,
      "name": "uv_gam_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```

```json
{
  "name": "uv_gam_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591262048,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:390",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591262048,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```

```json
{
  "name": "uv_gam_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591204830,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:390",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591204830,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```

```json
{
  "name": "uv_gam_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592076112,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:390",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_soc_phys_ram_to_gpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592076112,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```

```json
{
  "name": "uv_gam_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593842682,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:390",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_soc_phys_ram_to_gpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593842682,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "uv_gam_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627685982,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:390",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_soc_phys_ram_to_gpa"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```

```json
{
  "name": "uv_gam_range",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579299917,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:454",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579465622,
      "name": "uv_gam_range",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:454",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init",
        "arch/x86/platform/uv/tlb_uv.c:uv_soc_phys_ram_to_gpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299917,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071579460512,
      "name": "uv_gam_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071579472206,
      "name": "uv_gam_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```
</details>
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
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
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
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct uv_gam_range_s * uv_gam_range(long unsigned int pa)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

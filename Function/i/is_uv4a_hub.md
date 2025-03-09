# Function: <code>is_uv4a_hub</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_uv4a_hub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604781269,
      "name": "is_uv4a_hub",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:286",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604835608,
      "name": "is_uv4a_hub",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:286",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int is_uv4a_hub()
```

```json
{
  "name": "is_uv4a_hub",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324087,
      "name": "is_uv4a_hub",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:249",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34"
      ]
    },
    {
      "addr": 18446744071579488662,
      "name": "is_uv4a_hub",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:249",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324087,
      "name": "is_uv4a_hub",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_uv4a_hub",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604785410,
      "name": "is_uv4a_hub",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:286",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34",
        "arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604839765,
      "name": "is_uv4a_hub",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:286",
      "file": "arch/x86/platform/uv/tlb_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/tlb_uv.c:uv_bau_init"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int is_uv4a_hub()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int is_uv4a_hub()
```
</details>
</li>
</ul>

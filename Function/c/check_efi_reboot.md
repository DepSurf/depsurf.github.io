# Function: <code>check_efi_reboot</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void check_efi_reboot()
```

```json
{
  "name": "check_efi_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324167,
      "name": "check_efi_reboot",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:1431",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324167,
      "name": "check_efi_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void check_efi_reboot()
```

```json
{
  "name": "check_efi_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591262572,
      "name": "check_efi_reboot",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:1609",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591262572,
      "name": "check_efi_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void check_efi_reboot()
```

```json
{
  "name": "check_efi_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591205154,
      "name": "check_efi_reboot",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:1605",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591205154,
      "name": "check_efi_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void check_efi_reboot()
```

```json
{
  "name": "check_efi_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592076906,
      "name": "check_efi_reboot",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:1605",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592076906,
      "name": "check_efi_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_efi_reboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617045334,
      "name": "check_efi_reboot",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:1615",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_efi_reboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627686846,
      "name": "check_efi_reboot",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:1615",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_efi_reboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619444510,
      "name": "check_efi_reboot",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:1661",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "check_efi_reboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621740638,
      "name": "check_efi_reboot",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:1621",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
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
void check_efi_reboot()
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void check_efi_reboot()
```
</details>
</li>
</ul>

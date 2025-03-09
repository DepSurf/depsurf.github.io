# Function: <code>uv_early_read_mmr</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604775279,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:68",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604775279,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 146
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609124307,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:71",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609124307,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 71
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612190833,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:73",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612190833,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 142
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614331629,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:73",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614331629,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 139
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615261106,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:73",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615261106,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 139
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617037560,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:73",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617037560,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 107
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627672880,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:73",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627672880,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 99
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619430144,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:73",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619430144,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 99
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621726272,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:75",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid",
        "arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621726272,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 99
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr)
```

```json
{
  "name": "uv_early_read_mmr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604779420,
      "name": "uv_early_read_mmr",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:68",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604779420,
      "name": "uv_early_read_mmr",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 146
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr)
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
long unsigned int uv_early_read_mmr(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>

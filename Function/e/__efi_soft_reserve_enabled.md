# Function: <code>__efi_soft_reserve_enabled</code>

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
bool __efi_soft_reserve_enabled()
```

```json
{
  "name": "__efi_soft_reserve_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589048080,
      "name": "__efi_soft_reserve_enabled",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:79",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_map_regions",
        "arch/x86/platform/efi/efi.c:do_add_efi_memmap",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048080,
      "name": "__efi_soft_reserve_enabled",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled()
```

```json
{
  "name": "__efi_soft_reserve_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589056880,
      "name": "__efi_soft_reserve_enabled",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:83",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_map_regions",
        "arch/x86/platform/efi/efi.c:do_add_efi_memmap",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589056880,
      "name": "__efi_soft_reserve_enabled",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled()
```

```json
{
  "name": "__efi_soft_reserve_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588944128,
      "name": "__efi_soft_reserve_enabled",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:83",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_map_regions",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588944128,
      "name": "__efi_soft_reserve_enabled",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled()
```

```json
{
  "name": "__efi_soft_reserve_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589652656,
      "name": "__efi_soft_reserve_enabled",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:83",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_map_regions",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589652656,
      "name": "__efi_soft_reserve_enabled",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool __efi_soft_reserve_enabled()
```

```json
{
  "name": "__efi_soft_reserve_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591154848,
      "name": "__efi_soft_reserve_enabled",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:86",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591154848,
      "name": "__efi_soft_reserve_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool __efi_soft_reserve_enabled()
```

```json
{
  "name": "__efi_soft_reserve_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592882464,
      "name": "__efi_soft_reserve_enabled",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:90",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592882464,
      "name": "__efi_soft_reserve_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool __efi_soft_reserve_enabled()
```

```json
{
  "name": "__efi_soft_reserve_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593320944,
      "name": "__efi_soft_reserve_enabled",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:93",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593320944,
      "name": "__efi_soft_reserve_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool __efi_soft_reserve_enabled()
```

```json
{
  "name": "__efi_soft_reserve_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594077936,
      "name": "__efi_soft_reserve_enabled",
      "external": true,
      "loc": "drivers/firmware/efi/efi.c:94",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594077936,
      "name": "__efi_soft_reserve_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool __efi_soft_reserve_enabled()
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

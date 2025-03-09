# Function: <code>vmalloc_sync_mappings</code>

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
void vmalloc_sync_mappings()
```

```json
{
  "name": "vmalloc_sync_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579373872,
      "name": "vmalloc_sync_mappings",
      "external": true,
      "loc": "arch/x86/mm/fault.c:331",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373872,
      "name": "vmalloc_sync_mappings",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void vmalloc_sync_mappings()
```

```json
{
  "name": "vmalloc_sync_mappings",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492833576,
      "name": "vmalloc_sync_mappings",
      "external": true,
      "loc": "mm/vmalloc.c:3061",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492833576,
      "name": "vmalloc_sync_mappings",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void vmalloc_sync_mappings()
```

```json
{
  "name": "vmalloc_sync_mappings",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226637704,
      "name": "vmalloc_sync_mappings",
      "external": true,
      "loc": "mm/vmalloc.c:3061",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226637704,
      "name": "vmalloc_sync_mappings",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void vmalloc_sync_mappings()
```

```json
{
  "name": "vmalloc_sync_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286220592,
      "name": "vmalloc_sync_mappings",
      "external": true,
      "loc": "mm/vmalloc.c:3061",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286220592,
      "name": "vmalloc_sync_mappings",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void vmalloc_sync_mappings()
```

```json
{
  "name": "vmalloc_sync_mappings",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272787480,
      "name": "vmalloc_sync_mappings",
      "external": true,
      "loc": "mm/vmalloc.c:3061",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272787480,
      "name": "vmalloc_sync_mappings",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 26
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void vmalloc_sync_mappings()
```

```json
{
  "name": "vmalloc_sync_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579369776,
      "name": "vmalloc_sync_mappings",
      "external": true,
      "loc": "arch/x86/mm/fault.c:331",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369776,
      "name": "vmalloc_sync_mappings",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void vmalloc_sync_mappings()
```

```json
{
  "name": "vmalloc_sync_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299568,
      "name": "vmalloc_sync_mappings",
      "external": true,
      "loc": "arch/x86/mm/fault.c:331",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299568,
      "name": "vmalloc_sync_mappings",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void vmalloc_sync_mappings()
```

```json
{
  "name": "vmalloc_sync_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579369696,
      "name": "vmalloc_sync_mappings",
      "external": true,
      "loc": "arch/x86/mm/fault.c:331",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579369696,
      "name": "vmalloc_sync_mappings",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void vmalloc_sync_mappings()
```

```json
{
  "name": "vmalloc_sync_mappings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378176,
      "name": "vmalloc_sync_mappings",
      "external": true,
      "loc": "arch/x86/mm/fault.c:331",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/notifier.c:register_die_notifier",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378176,
      "name": "vmalloc_sync_mappings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void vmalloc_sync_mappings()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void vmalloc_sync_mappings()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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

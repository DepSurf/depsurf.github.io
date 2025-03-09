# Function: <code>__alloc_bootmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * __alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__alloc_bootmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595142872,
      "name": "__alloc_bootmem",
      "external": true,
      "loc": "mm/nobootmem.c:308",
      "file": "mm/nobootmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklist",
        "init/main.c:initcall_blacklist",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/kernel/e820.c:e820_reserve_resources",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:spp_getpage",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595142872,
      "name": "__alloc_bootmem",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * __alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__alloc_bootmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595313947,
      "name": "__alloc_bootmem",
      "external": true,
      "loc": "mm/nobootmem.c:309",
      "file": "mm/nobootmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklist",
        "init/main.c:initcall_blacklist",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/kernel/e820.c:e820_reserve_resources",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:spp_getpage",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595313947,
      "name": "__alloc_bootmem",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * __alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__alloc_bootmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595562241,
      "name": "__alloc_bootmem",
      "external": true,
      "loc": "mm/nobootmem.c:312",
      "file": "mm/nobootmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklist",
        "init/main.c:initcall_blacklist",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/kernel/e820.c:e820_reserve_resources",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:spp_getpage",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595562241,
      "name": "__alloc_bootmem",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void * __alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__alloc_bootmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596489094,
      "name": "__alloc_bootmem",
      "external": true,
      "loc": "mm/nobootmem.c:296",
      "file": "mm/nobootmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklist",
        "init/main.c:initcall_blacklist",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:spp_getpage",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596489094,
      "name": "__alloc_bootmem",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void * __alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__alloc_bootmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602815910,
      "name": "__alloc_bootmem",
      "external": true,
      "loc": "mm/nobootmem.c:297",
      "file": "mm/nobootmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklist",
        "init/main.c:initcall_blacklist",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:spp_getpage",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602815910,
      "name": "__alloc_bootmem",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void * __alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__alloc_bootmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602989156,
      "name": "__alloc_bootmem",
      "external": true,
      "loc": "mm/nobootmem.c:297",
      "file": "mm/nobootmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:initcall_blacklist",
        "init/main.c:initcall_blacklist",
        "arch/x86/xen/p2m.c:alloc_p2m_page",
        "arch/x86/kernel/e820.c:e820__reserve_resources",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_hpet",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:spp_getpage",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602989156,
      "name": "__alloc_bootmem",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void * __alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal)
```
</details>
</li>
</ul>

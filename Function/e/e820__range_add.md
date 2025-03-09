# Function: <code>e820__range_add</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596324021,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:148",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_auto_xlated_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596324021,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602642059,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:168",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_auto_xlated_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602642059,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602811746,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:169",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_auto_xlated_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602811746,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604606793,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:168",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604606793,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604702401,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604702401,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604714789,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604714789,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609061424,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:do_add_efi_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609061424,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612124784,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:do_add_efi_memmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612124784,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614264705,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614264705,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615186037,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615186037,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616952589,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616952589,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627571836,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627563888,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619323712,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619314304,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621616832,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table"
      ],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621607424,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 273
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604641079,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604641079,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604609013,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604609013,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604718871,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604718871,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```

```json
{
  "name": "e820__range_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604718901,
      "name": "e820__range_add",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:182",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:e820__memory_setup_default",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820__range_remove",
        "arch/x86/kernel/e820.c:__append_e820_table",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604718901,
      "name": "e820__range_add",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
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
void e820__range_add(u64 start, u64 size, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void e820__range_add(u64 start, u64 size, enum e820_type type)
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

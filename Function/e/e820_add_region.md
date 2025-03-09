# Function: <code>e820_add_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void e820_add_region(u64 start, u64 size, int type)
```

```json
{
  "name": "e820_add_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594998413,
      "name": "e820_add_region",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:129",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_auto_xlated_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:__append_e820_map",
        "arch/x86/kernel/e820.c:e820_remove_range",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:default_machine_specific_memory_setup",
        "arch/x86/kernel/e820.c:default_machine_specific_memory_setup",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_stolen",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594998413,
      "name": "e820_add_region",
      "section": ".init.text",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void e820_add_region(u64 start, u64 size, int type)
```

```json
{
  "name": "e820_add_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595161909,
      "name": "e820_add_region",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:129",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_auto_xlated_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:default_machine_specific_memory_setup",
        "arch/x86/kernel/e820.c:default_machine_specific_memory_setup",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820_remove_range",
        "arch/x86/kernel/e820.c:__append_e820_map",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595161909,
      "name": "e820_add_region",
      "section": ".init.text",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void e820_add_region(u64 start, u64 size, int type)
```

```json
{
  "name": "e820_add_region",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595404552,
      "name": "e820_add_region",
      "external": true,
      "loc": "arch/x86/kernel/e820.c:131",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_auto_xlated_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:default_machine_specific_memory_setup",
        "arch/x86/kernel/e820.c:default_machine_specific_memory_setup",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:e820_remove_range",
        "arch/x86/kernel/e820.c:__append_e820_map",
        "arch/x86/kernel/acpi/boot.c:arch_reserve_mem_area",
        "arch/x86/kernel/early-quirks.c:intel_graphics_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595404552,
      "name": "e820_add_region",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void e820_add_region(u64 start, u64 size, int type)
```
</details>
</li>
</ul>

# Function: <code>memblock_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587358768,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:756",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/head.c:reserve_ebda_region",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_set_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/nobootmem.c:__alloc_memory_core_early",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587358768,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587859669,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:730",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_set_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/nobootmem.c:__alloc_memory_core_early",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/esrt.c:efi_esrt_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587859669,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588074365,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:730",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/nobootmem.c:__alloc_memory_core_early",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588074365,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588300634,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:714",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/nobootmem.c:__alloc_memory_core_early",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588300634,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588865891,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:714",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/nobootmem.c:__alloc_memory_core_early",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588865891,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589244902,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:722",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/nobootmem.c:__alloc_memory_core_early",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_virt_alloc_internal",
        "mm/memblock.c:memblock_alloc_base_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_alloc_range",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589244902,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589487206,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:830",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_alloc_internal",
        "mm/memblock.c:memblock_alloc_base_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_alloc_range",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589487206,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589947933,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589947933,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590175373,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590175373,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591194500,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:823",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel_low",
        "arch/x86/kernel/setup.c:relocate_initrd",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/crash.c:crash_reserve_low_1M",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:allocate_aperture",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591194500,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591689382,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:810",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/crash.c:crash_reserve_low_1M",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:allocate_aperture",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "drivers/acpi/tables.c:acpi_reserve_initial_tables",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591689382,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591632232,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:810",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "init/initramfs.c:reserve_initrd_mem",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/crash.c:crash_reserve_low_1M",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "drivers/acpi/tables.c:acpi_reserve_initial_tables",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591632232,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592806143,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:837",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "init/initramfs.c:reserve_initrd_mem",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "drivers/acpi/tables.c:acpi_reserve_initial_tables",
        "drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592806143,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594706136,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:838",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "init/initramfs.c:reserve_initrd_mem",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "drivers/acpi/tables.c:acpi_reserve_initial_tables",
        "drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594706136,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596448560,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:853",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "init/initramfs.c:reserve_initrd_mem",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest",
        "drivers/acpi/tables.c:acpi_reserve_initial_tables",
        "drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596448560,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596989872,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:866",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:reserve_initrd_mem",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest",
        "drivers/acpi/tables.c:acpi_reserve_initial_tables",
        "drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596989872,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597918576,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:906",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:reserve_initrd_mem",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/setup.c:parse_setup_data",
        "arch/x86/kernel/e820.c:e820__memblock_setup",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest",
        "drivers/acpi/tables.c:acpi_reserve_initial_tables",
        "drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597918576,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492893992,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/setup.c:setup_arch",
        "arch/arm64/mm/init.c:arm64_memblock_init",
        "arch/arm64/mm/init.c:arm64_memblock_init",
        "arch/arm64/mm/init.c:arm64_memblock_init",
        "arch/arm64/mm/init.c:arm64_memblock_init",
        "arch/arm64/mm/numa.c:numa_init",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/arm-init.c:efi_init",
        "drivers/firmware/efi/arm-init.c:reserve_regions",
        "drivers/of/fdt.c:early_init_dt_reserve_memory_arch",
        "drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492893992,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226691112,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/mm/init.c:arm_memblock_init",
        "arch/arm/mm/init.c:arm_memblock_init",
        "arch/arm/mm/mmu.c:arm_mm_memblock_reserve",
        "arch/arm/mach-hisi/platmcpm.c:hip04_smp_init",
        "arch/arm/mach-mvebu/board-v7.c:mvebu_scan_mem",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:early_memtest",
        "mm/memtest.c:early_memtest",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/arm-init.c:efi_init",
        "drivers/firmware/efi/arm-init.c:reserve_regions",
        "drivers/of/fdt.c:early_init_dt_reserve_memory_arch",
        "drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226691112,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286293696,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/prom.c:early_init_devtree",
        "arch/powerpc/kernel/fadump.c:fadump_reserve_mem",
        "arch/powerpc/kernel/fadump.c:fadump_reserve_mem",
        "arch/powerpc/kernel/machine_kexec.c:reserve_crashkernel",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_dt_scan_hugepage_blocks",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/of/fdt.c:early_init_dt_reserve_memory_arch",
        "drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286293696,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270894292,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/init.c:setup_bootmem",
        "arch/riscv/mm/init.c:setup_bootmem",
        "arch/riscv/mm/init.c:setup_bootmem",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/of/fdt.c:early_init_dt_reserve_memory_arch",
        "drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270894292,
      "name": "memblock_reserve",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589777661,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589777661,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589500484,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589500484,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590221069,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590221069,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int memblock_reserve(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590271427,
      "name": "memblock_reserve",
      "external": true,
      "loc": "mm/memblock.c:827",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ebda.c:reserve_bios_regions",
        "arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init",
        "arch/x86/xen/setup.c:xen_add_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_find_free_area",
        "arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/xen/mmu_pv.c:xen_reserve_special_pages",
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/mpparse.c:smp_scan_config",
        "arch/x86/kernel/check.c:setup_bios_corruption_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/quirks.c:efi_reserve_boot_services",
        "arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_alloc_range_nid",
        "mm/memblock.c:memblock_double_array",
        "mm/memtest.c:reserve_bad_mem",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_config_parse_tables",
        "drivers/firmware/efi/efi.c:efi_mem_reserve",
        "drivers/firmware/efi/memattr.c:efi_memattr_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init",
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590271427,
      "name": "memblock_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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

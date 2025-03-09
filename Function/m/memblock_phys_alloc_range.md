# Function: <code>memblock_phys_alloc_range</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604892182,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1411",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604892182,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604926087,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1408",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604926087,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609240509,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1421",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609240509,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 23
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612306918,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1380",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel_low",
        "arch/x86/kernel/setup.c:relocate_initrd",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612306918,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 113
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614446735,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1381",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614446735,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 113
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615389653,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1416",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615389653,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 113
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617179661,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1423",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617179661,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627871360,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1441",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627871360,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 134
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619636368,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1463",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619636368,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 134
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621939776,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1521",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "arch/x86/platform/efi/memmap.c:efi_memmap_alloc",
        "kernel/crash_core.c:reserve_crashkernel_generic",
        "kernel/crash_core.c:reserve_crashkernel_generic",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621939776,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 134
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510965332,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1408",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/mmu.c:early_pgtable_alloc",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510965332,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 80
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243451864,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1408",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/init.c:arm_memblock_steal",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243451864,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 44
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302618816,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1408",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtas.c:rtas_initialize",
        "arch/powerpc/mm/book3s64/hash_utils.c:htab_initialize",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302618816,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270691658,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1408",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/init.c:create_pgd_mapping",
        "arch/riscv/mm/init.c:create_pgd_mapping",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270691658,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 68
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604831547,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1408",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604831547,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604800608,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1408",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604800608,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604908731,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1408",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604908731,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 20
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
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```

```json
{
  "name": "memblock_phys_alloc_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604930268,
      "name": "memblock_phys_alloc_range",
      "external": true,
      "loc": "mm/memblock.c:1408",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__memblock_alloc_reserved",
        "mm/cma.c:cma_declare_contiguous",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/firmware/efi/memmap.c:efi_memmap_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604930268,
      "name": "memblock_phys_alloc_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
phys_addr_t memblock_phys_alloc_range(phys_addr_t size, phys_addr_t align, phys_addr_t start, phys_addr_t end)
```
</details>
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

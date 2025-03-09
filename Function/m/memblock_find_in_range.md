# Function: <code>memblock_find_in_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587357366,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:264",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/numa.c:numa_set_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357366,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587858278,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:260",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_set_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587858278,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588072974,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:260",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588072974,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588299396,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:248",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588299396,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588864653,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:248",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588864653,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589243664,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:251",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243664,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589485935,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:328",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589485935,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589946510,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
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
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589946510,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590174053,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
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
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590174053,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591192397,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:331",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_crashkernel_low",
        "arch/x86/kernel/setup.c:relocate_initrd",
        "arch/x86/kernel/aperture_64.c:allocate_aperture",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591192397,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591687279,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:316",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/aperture_64.c:allocate_aperture",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591687279,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591630133,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:316",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:reserve_real_mode",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591630133,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592804046,
      "name": "memblock_find_in_range",
      "external": false,
      "loc": "mm/memblock.c:318",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592804046,
      "name": "memblock_find_in_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "memblock_find_in_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594704652,
      "name": "memblock_find_in_range",
      "external": false,
      "loc": "mm/memblock.c:318",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594704652,
      "name": "memblock_find_in_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596446464,
      "name": "memblock_find_in_range",
      "external": false,
      "loc": "mm/memblock.c:322",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596446464,
      "name": "memblock_find_in_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596987744,
      "name": "memblock_find_in_range",
      "external": false,
      "loc": "mm/memblock.c:322",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596987744,
      "name": "memblock_find_in_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597916432,
      "name": "memblock_find_in_range",
      "external": false,
      "loc": "mm/memblock.c:328",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597916432,
      "name": "memblock_find_in_range.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492892112,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/init.c:arm64_memblock_init",
        "arch/arm64/mm/numa.c:numa_init",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade",
        "drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492892112,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226689288,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/setup.c:setup_arch",
        "arch/arm/kernel/setup.c:setup_arch",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226689288,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286291472,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/fadump.c:fadump_reserve_mem",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286291472,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270893184,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/of/of_reserved_mem.c:early_init_dt_alloc_reserved_memory_arch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270893184,
      "name": "memblock_find_in_range",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 112
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589776341,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
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
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589776341,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589499164,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
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
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589499164,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590219749,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
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
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590219749,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
```

```json
{
  "name": "memblock_find_in_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590270107,
      "name": "memblock_find_in_range",
      "external": true,
      "loc": "mm/memblock.c:335",
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
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:alloc_low_pages",
        "arch/x86/mm/numa.c:numa_alloc_distance",
        "mm/memblock.c:memblock_double_array",
        "mm/memblock.c:memblock_double_array",
        "drivers/acpi/tables.c:acpi_table_upgrade"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590270107,
      "name": "memblock_find_in_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
phys_addr_t memblock_find_in_range(phys_addr_t start, phys_addr_t end, phys_addr_t size, phys_addr_t align)
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

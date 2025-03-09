# Function: <code>memblock_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587359289,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:730",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_free_ro_pages",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "mm/nobootmem.c:free_bootmem_node",
        "mm/nobootmem.c:free_bootmem",
        "mm/memblock.c:memblock_double_array",
        "mm/memory_hotplug.c:remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359289,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587860202,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:719",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_free_ro_pages",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "mm/nobootmem.c:free_bootmem",
        "mm/nobootmem.c:free_bootmem_node",
        "mm/memblock.c:memblock_double_array",
        "mm/memory_hotplug.c:remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860202,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588074898,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:719",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_free_ro_pages",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "mm/nobootmem.c:free_bootmem",
        "mm/nobootmem.c:free_bootmem_node",
        "mm/memblock.c:memblock_double_array",
        "mm/memory_hotplug.c:remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588074898,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588301215,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:703",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/kvmclock.c:kvmclock_init",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "mm/nobootmem.c:free_bootmem",
        "mm/nobootmem.c:free_bootmem_node",
        "mm/memblock.c:memblock_double_array",
        "mm/memory_hotplug.c:remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588301215,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588866472,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:703",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/kvmclock.c:kvm_memblock_free",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "mm/nobootmem.c:free_bootmem",
        "mm/nobootmem.c:free_bootmem_node",
        "mm/memblock.c:memblock_double_array",
        "mm/memory_hotplug.c:remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588866472,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245578,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:711",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/kvmclock.c:kvm_memblock_free",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "mm/nobootmem.c:free_bootmem",
        "mm/nobootmem.c:free_bootmem_node",
        "mm/memblock.c:memblock_double_array",
        "mm/memory_hotplug.c:remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245578,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589487882,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:819",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/kernel/tce_64.c:free_tce_table",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_init_nid",
        "mm/memory_hotplug.c:__remove_memory",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589487882,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589948601,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/kernel/tce_64.c:free_tce_table",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_init_nid",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589948601,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590176041,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/kernel/tce_64.c:free_tce_table",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590176041,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591193671,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:812",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_initrd",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "lib/bootconfig.c:xbc_destroy_all",
        "lib/cpumask.c:free_bootmem_cpumask_var",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:xdbc_free_ring",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591193671,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591688553,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:799",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup.c:reserve_initrd",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "lib/bootconfig.c:xbc_destroy_all",
        "lib/cpumask.c:free_bootmem_cpumask_var",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_free_ring",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591688553,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591631401,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:799",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "lib/bootconfig.c:xbc_destroy_all",
        "lib/cpumask.c:free_bootmem_cpumask_var",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_free_ring",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591631401,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592805261,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:826",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/mm/init.c:init_mem_mapping",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/memblock.c:memblock_free_ptr",
        "mm/sparse.c:sparse_buffer_free",
        "lib/cpumask.c:free_bootmem_cpumask_var",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init_early",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_free_ring",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/firmware/efi/memmap.c:__efi_memmap_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592805261,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void memblock_free(void * ptr, size_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594707027,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:813",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:print_unknown_bootoptions",
        "init/main.c:xbc_make_cmdline",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/dma/swiotlb.c:swiotlb_init_remap",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "lib/bootconfig.c:xbc_exit",
        "lib/bootconfig.c:xbc_exit",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594707027,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void memblock_free(void * ptr, size_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596446968,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:828",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_double_array"
      ],
      "caller_func": [
        "init/main.c:print_unknown_bootoptions",
        "init/main.c:xbc_make_cmdline",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/mm/numa.c:numa_init",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/dma/swiotlb.c:swiotlb_init_remap",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/sparse.c:sparse_buffer_alloc",
        "mm/sparse.c:sparse_buffer_fini",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596450400,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void memblock_free(void * ptr, size_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596988248,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:841",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_double_array"
      ],
      "caller_func": [
        "init/main.c:print_unknown_bootoptions",
        "init/main.c:xbc_make_cmdline",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/mm/numa.c:numa_init",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/dma/swiotlb.c:swiotlb_init_remap",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/sparse.c:sparse_buffer_alloc",
        "mm/sparse.c:sparse_buffer_fini",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596991728,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void memblock_free(void * ptr, size_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597916936,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:881",
      "file": "mm/memblock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memblock.c:memblock_double_array"
      ],
      "caller_func": [
        "init/main.c:print_unknown_bootoptions",
        "init/main.c:xbc_make_cmdline",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/mm/numa.c:numa_init",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/printk/printk.c:setup_log_buf",
        "kernel/dma/swiotlb.c:swiotlb_init_remap",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/sparse.c:sparse_buffer_alloc",
        "mm/sparse.c:sparse_buffer_fini",
        "mm/kfence/core.c:kfence_alloc_pool_and_metadata",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/bootconfig.c:xbc_init",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597920864,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492894912,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/init.c:free_initrd_mem",
        "arch/arm64/mm/mmu.c:paging_init",
        "arch/arm64/mm/numa.c:pcpu_fc_free",
        "arch/arm64/mm/numa.c:numa_free_distance",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492894912,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226692040,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/init.c:mem_init",
        "arch/arm/mm/init.c:arm_memblock_steal",
        "arch/arm/mach-hisi/platmcpm.c:hip04_smp_init",
        "mm/percpu.c:pcpu_dfl_fc_free",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/memblock.c:memblock_double_array",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226692040,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286294848,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:setup_arch",
        "arch/powerpc/kernel/setup_64.c:pcpu_fc_free",
        "arch/powerpc/kernel/paca.c:free_unused_pacas",
        "arch/powerpc/kernel/paca.c:free_unused_pacas",
        "arch/powerpc/kernel/dt_cpu_ftrs.c:dt_cpu_ftrs_scan_callback",
        "arch/powerpc/kernel/ima_kexec.c:ima_free_kexec_buffer",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286294848,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270894826,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_dfl_fc_free",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/of/of_reserved_mem.c:fdt_init_reserved_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270894826,
      "name": "memblock_free",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589778329,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/kernel/tce_64.c:free_tce_table",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589778329,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589501152,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/kernel/tce_64.c:free_tce_table",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/cma.c:cma_declare_contiguous",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589501152,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590221737,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/kernel/tce_64.c:free_tce_table",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590221737,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int memblock_free(phys_addr_t base, phys_addr_t size)
```

```json
{
  "name": "memblock_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590272095,
      "name": "memblock_free",
      "external": true,
      "loc": "mm/memblock.c:816",
      "file": "mm/memblock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/setup.c:xen_del_extra_mem",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/setup.c:xen_memory_setup",
        "arch/x86/xen/p2m.c:free_p2m_page",
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_free_ro_pages",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/setup.c:reserve_crashkernel",
        "arch/x86/kernel/setup_percpu.c:pcpu_fc_free",
        "arch/x86/kernel/tce_64.c:free_tce_table",
        "arch/x86/mm/numa.c:numa_reset_distance",
        "kernel/dma/swiotlb.c:swiotlb_init",
        "mm/percpu.c:pcpu_page_first_chunk",
        "mm/percpu.c:pcpu_embed_first_chunk",
        "mm/percpu.c:pcpu_free_alloc_info",
        "mm/page_alloc.c:free_bootmem_with_active_regions",
        "mm/memblock.c:memblock_double_array",
        "mm/sparse.c:sparse_buffer_free",
        "mm/memory_hotplug.c:try_remove_memory",
        "mm/cma.c:cma_declare_contiguous",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware",
        "lib/cpumask.c:free_bootmem_cpumask_var"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590272095,
      "name": "memblock_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * ptr</code>
</li>
<li>
<b>Param removed. </b>
<code>phys_addr_t base</code>
</li>
<li>
<b>Param type changed. </b>
<code>phys_addr_t size</code> ➡️ <code>size_t size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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

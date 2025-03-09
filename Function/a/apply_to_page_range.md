# Function: <code>apply_to_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580681200,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:1879",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:do_remap_gfn",
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580681200,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1111
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580794368,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:1942",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:do_remap_gfn",
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580794368,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1083
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580858640,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:1942",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu.c:do_remap_gfn",
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580858640,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1079
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580903488,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2148",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903488,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1038
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002960,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2265",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002960,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1195
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141664,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2307",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141664,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1109
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581216304,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2043",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581216304,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2097",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "mm/vmalloc.c:alloc_vm_area",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581299840,
      "name": "apply_to_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581289648,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348384,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2102",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "mm/vmalloc.c:alloc_vm_area",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348384,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546592,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2364",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "mm/vmalloc.c:alloc_vm_area",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range",
        "drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546592,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581589840,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2543",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "mm/vmalloc.c:vmap_pfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range",
        "drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589840,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612160,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2604",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "mm/vmalloc.c:vmap_pfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range",
        "drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612160,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581879168,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2699",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "mm/vmalloc.c:vmap_pfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range",
        "drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581879168,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582278800,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2792",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "mm/vmalloc.c:vmap_pfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range",
        "drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582278800,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582771280,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2763",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "mm/vmalloc.c:vmap_pfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range",
        "drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582771280,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582987424,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2763",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "mm/vmalloc.c:vmap_pfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range",
        "drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987424,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583162768,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2786",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/grant-table.c:arch_gnttab_valloc",
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "mm/vmalloc.c:vmap_pfn",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range",
        "drivers/xen/xlate_mmu.c:xen_xlate_remap_gfn_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583162768,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492756112,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2102",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/efi.c:efi_set_mapping_permissions",
        "arch/arm64/mm/pageattr.c:set_direct_map_default_noflush",
        "arch/arm64/mm/pageattr.c:set_direct_map_invalid_noflush",
        "arch/arm64/mm/pageattr.c:__change_memory_common",
        "mm/vmalloc.c:alloc_vm_area",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492756112,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226567084,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2102",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/efi.c:efi_set_mapping_permissions",
        "arch/arm/mm/dma-mapping.c:__dma_remap",
        "arch/arm/mm/pageattr.c:change_memory_common",
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226567084,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286117792,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2102",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286117792,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1524
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272737798,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2102",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272737798,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317232,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2102",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "mm/vmalloc.c:alloc_vm_area",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317232,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581261360,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2102",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:alloc_vm_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581261360,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1035
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308432,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2102",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "mm/vmalloc.c:alloc_vm_area",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308432,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1037
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
int apply_to_page_range(struct mm_struct * mm, long unsigned int addr, long unsigned int size, pte_fn_t fn, void * data)
```

```json
{
  "name": "apply_to_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581372432,
      "name": "apply_to_page_range",
      "external": true,
      "loc": "mm/memory.c:2102",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_remap_pfn",
        "mm/vmalloc.c:alloc_vm_area",
        "drivers/xen/xlate_mmu.c:xen_remap_vma_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372432,
      "name": "apply_to_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1034
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

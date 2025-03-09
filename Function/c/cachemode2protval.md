# Function: <code>cachemode2protval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595063566,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579297871,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_pages_array"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304962,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:track_pfn_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:345",
      "file": "arch/x86/pci/i386.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595204860,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579205924,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595229251,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579286097,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298134,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301525,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583804690,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530293,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816131,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dma_common_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595481142,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586535174,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586558543,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/pci/i386.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/i386.c:pci_mmap_page_range",
        "arch/x86/pci/i386.c:pci_mmap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595447766,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579217588,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595472301,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301489,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313653,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316933,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583943954,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584712421,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009235,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dma_common_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595734093,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586716870,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586740184,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:383",
      "file": "arch/x86/pci/i386.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/i386.c:pci_mmap_page_range",
        "arch/x86/pci/i386.c:pci_mmap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596368647,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579214957,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596393931,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299203,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311057,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314373,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797431,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583991976,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584793909,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585094851,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dma_common_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596661992,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586843270,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:420",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602686723,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579232621,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602712581,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319930,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333233,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337253,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060679,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584207804,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585214197,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585520611,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "drivers/base/dma-mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/dma-mapping.c:dma_common_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602992596,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587330918,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:445",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602858171,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244874,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602885233,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330712,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344090,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348357,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944452,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_common_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584260040,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584428330,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585451189,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603164353,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587632824,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:444",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604655108,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268650,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604682243,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356912,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370730,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375301,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579993092,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/dma/mapping.c:dma_common_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349831,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584524714,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585574453,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604969859,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587761736,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:468",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604753586,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282899,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604781738,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371002,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385770,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_array",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390821,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584544624,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584723205,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585794520,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605078948,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588066321,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604767004,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285363,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604807505,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375661,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389162,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394133,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584679838,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584859365,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585937272,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587061944,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605118442,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588272129,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm)
```

```json
{
  "name": "cachemode2protval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579385920,
      "name": "cachemode2protval",
      "external": true,
      "loc": "arch/x86/mm/init.c:61",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:pgprot_writethrough",
        "arch/x86/mm/pat/memtype.c:pgprot_writecombine",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/hpet.c:hpet_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/vme/vme.c:vme_master_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579385920,
      "name": "cachemode2protval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long unsigned int cachemode2protval(enum page_cache_mode pcm)
```

```json
{
  "name": "cachemode2protval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391408,
      "name": "cachemode2protval",
      "external": true,
      "loc": "arch/x86/mm/init.c:62",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:pgprot_writethrough",
        "arch/x86/mm/pat/memtype.c:pgprot_writecombine",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/hpet.c:hpet_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/vme/vme.c:vme_master_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391408,
      "name": "cachemode2protval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long unsigned int cachemode2protval(enum page_cache_mode pcm)
```

```json
{
  "name": "cachemode2protval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394736,
      "name": "cachemode2protval",
      "external": true,
      "loc": "arch/x86/mm/init.c:62",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:pgprot_writethrough",
        "arch/x86/mm/pat/memtype.c:pgprot_writecombine",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/hpet.c:hpet_mmap",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/vme/vme.c:vme_master_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394736,
      "name": "cachemode2protval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long unsigned int cachemode2protval(enum page_cache_mode pcm)
```

```json
{
  "name": "cachemode2protval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456672,
      "name": "cachemode2protval",
      "external": true,
      "loc": "arch/x86/mm/init.c:62",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:pgprot_writethrough",
        "arch/x86/mm/pat/memtype.c:pgprot_writecombine",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/hpet.c:hpet_mmap",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_mmap",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/vme/vme.c:vme_master_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456672,
      "name": "cachemode2protval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
long unsigned int cachemode2protval(enum page_cache_mode pcm)
```

```json
{
  "name": "cachemode2protval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579531344,
      "name": "cachemode2protval",
      "external": true,
      "loc": "arch/x86/mm/init.c:61",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:pgprot_writethrough",
        "arch/x86/mm/pat/memtype.c:pgprot_writecombine",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/hpet.c:hpet_mmap",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_mmap",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/vme/vme.c:vme_master_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531344,
      "name": "cachemode2protval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int cachemode2protval(enum page_cache_mode pcm)
```

```json
{
  "name": "cachemode2protval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579634672,
      "name": "cachemode2protval",
      "external": true,
      "loc": "arch/x86/mm/init.c:62",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:pgprot_writethrough",
        "arch/x86/mm/pat/memtype.c:pgprot_writecombine",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/video/fbdev/core/fbmem.c:fb_mmap",
        "drivers/char/hpet.c:hpet_mmap",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/staging/vme_user/vme.c:vme_master_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634672,
      "name": "cachemode2protval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int cachemode2protval(enum page_cache_mode pcm)
```

```json
{
  "name": "cachemode2protval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648720,
      "name": "cachemode2protval",
      "external": true,
      "loc": "arch/x86/mm/init.c:63",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:pgprot_writethrough",
        "arch/x86/mm/pat/memtype.c:pgprot_writecombine",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/char/hpet.c:hpet_mmap",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/staging/vme_user/vme.c:vme_master_mmap",
        "arch/x86/video/fbdev.c:fb_pgprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648720,
      "name": "cachemode2protval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
long unsigned int cachemode2protval(enum page_cache_mode pcm)
```

```json
{
  "name": "cachemode2protval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579682592,
      "name": "cachemode2protval",
      "external": true,
      "loc": "arch/x86/mm/init.c:62",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:apic_set_fixmap",
        "arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_pages_array",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wt",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:_set_memory_wc",
        "arch/x86/mm/pat/set_memory.c:set_memory_uc",
        "arch/x86/mm/pat/memtype.c:pgprot_writethrough",
        "arch/x86/mm/pat/memtype.c:pgprot_writecombine",
        "arch/x86/mm/pat/memtype.c:track_pfn_insert",
        "arch/x86/mm/pat/memtype.c:track_pfn_remap",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:reserve_pfn_range",
        "arch/x86/mm/pat/memtype.c:phys_mem_access_prot_allowed",
        "mm/memremap.c:memremap_pages",
        "drivers/pci/mmap.c:pci_mmap_resource_range",
        "drivers/char/hpet.c:hpet_mmap",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/staging/vme_user/vme.c:vme_master_mmap",
        "arch/x86/video/fbdev.c:pgprot_framebuffer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579682592,
      "name": "cachemode2protval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604693283,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284067,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604721447,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371565,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385066,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390037,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584630320,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584810549,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585698248,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605016388,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587883825,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604660803,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219363,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604689384,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301757,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314490,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319589,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584560126,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584741317,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585557592,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586709864,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604981848,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587603105,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604770867,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285267,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604799014,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371485,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384986,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389957,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584629998,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584811973,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585887288,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016504,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605098981,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588209185,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cachemode2protval",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604771124,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:register_lapic_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291155,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:mp_register_ioapic",
        "arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604811633,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379965,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/ioremap.c:early_memremap_decrypted_wp",
        "arch/x86/mm/ioremap.c:early_memremap_encrypted_wp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393498,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_pages_array",
        "arch/x86/mm/pageattr.c:_set_memory_wt",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_wc",
        "arch/x86/mm/pageattr.c:_set_memory_uc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398485,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pgprot_writethrough",
        "arch/x86/mm/pat.c:pgprot_writecombine",
        "arch/x86/mm/pat.c:track_pfn_insert",
        "arch/x86/mm/pat.c:track_pfn_remap",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:reserve_pfn_range",
        "arch/x86/mm/pat.c:phys_mem_access_prot_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "kernel/dma/mapping.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584737694,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/pci/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/mmap.c:pci_mmap_resource_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584917045,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/video/fbdev/core/fbmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbmem.c:fb_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585995672,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/char/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/hpet.c:hpet_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587123672,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605122636,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/usb/early/ehci-dbgp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588344849,
      "name": "cachemode2protval",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_types.h:467",
      "file": "drivers/vme/vme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vme/vme.c:vme_master_mmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int cachemode2protval(enum page_cache_mode pcm)
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

# Function: <code>pgd_offset_pgd</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_offset_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609014894,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609045372,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075877,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138370,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392504,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401561,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413293,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:sync_current_stack_to_mm",
        "arch/x86/mm/tlb.c:sync_current_stack_to_mm",
        "arch/x86/mm/tlb.c:sync_current_stack_to_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432370,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_mm",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591186851,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609155758,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579466274,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609172396,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog",
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog",
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog",
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512209,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520981,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593650,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596229,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605044,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581609684,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616245,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626805,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:map_kernel_range_noflush",
        "mm/vmalloc.c:unmap_kernel_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720450,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762325,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591198231,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880394,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581914421,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992676,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022789,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458480,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585045710,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_offset_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612076898,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612108728,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579078357,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591250886,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396796,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579431794,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_mm",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591682166,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612226253,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462630,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190689,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552337,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595957,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639666,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642453,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652191,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657076,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663237,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672501,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:map_kernel_range_noflush",
        "mm/vmalloc.c:unmap_kernel_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696524,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768354,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810405,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591693122,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926410,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581961301,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042244,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071221,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515392,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_offset_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614215405,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614248580,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579085253,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591194704,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400097,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434754,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_mm",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591625663,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614367079,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579464975,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220196,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574674,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618597,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581661234,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664053,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673164,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678516,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685285,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698821,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795082,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838837,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635621,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951772,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581987269,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068713,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096277,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545008,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:104",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
pgd_t * pgd_offset_pgd(pgd_t * pgd, long unsigned int address)
```

```json
{
  "name": "pgd_offset_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615134214,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615168756,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108304,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592060505,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462421,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 18446744071579498979,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_mm",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592799081,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579518898,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_clone_p4d"
      ]
    },
    {
      "addr": 18446744071579530389,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460167,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839270,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886289,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581929574,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581932413,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942501,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947756,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581954749,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970624,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079008,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129714,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582170853,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    },
    {
      "addr": 18446744071582256483,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582289375,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382782,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411090,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861133,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:123",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592082659,
      "name": "pgd_offset_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579518736,
      "name": "pgd_offset_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071592092499,
      "name": "pgd_offset_pgd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071582170496,
      "name": "pgd_offset_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071592216079,
      "name": "pgd_offset_pgd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
pgd_t * pgd_offset_pgd(pgd_t * pgd, long unsigned int address)
```

```json
{
  "name": "pgd_offset_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616897538,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616934809,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140303,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct",
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827012,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538886,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:set_pte_vaddr"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 18446744071579580435,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594699200,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603024,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": [
        "arch/x86/mm/pti.c:pti_clone_p4d"
      ]
    },
    {
      "addr": 18446744071579617301,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807404,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617165399,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231428,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242585,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582336979,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582340925,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352098,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357037,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369997,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582393792,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518759,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576722,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582630414,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": [
        "mm/sparse-vmemmap.c:__populate_section_memmap",
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ]
    },
    {
      "addr": 18446744071582743615,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582773824,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885453,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582924002,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431661,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533120,
      "name": "pgd_offset_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071593849848,
      "name": "pgd_offset_pgd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579602832,
      "name": "pgd_offset_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071593859644,
      "name": "pgd_offset_pgd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071582628672,
      "name": "pgd_offset_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071593994781,
      "name": "pgd_offset_pgd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
  "name": "pgd_offset_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491393,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627540753,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184655,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct",
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270732,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642310,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690003,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596439550,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627732127,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729349,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234012,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627851636,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722304,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738233,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838018,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842541,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853394,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582859021,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871469,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900048,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:__vunmap_range_noflush",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036979,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095618,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121530,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596453919,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275276,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583435069,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583479554,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019661,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:124",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_offset_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235521,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619286929,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188722,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct",
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277052,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656358,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579703763,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596980366,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619491359,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579775831,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437239,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619628532,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938071,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582953823,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583054179,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058288,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069778,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583074528,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088304,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115184,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:__vunmap_range_noflush",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245988,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305461,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331802,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596995247,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491769,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583650064,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583696133,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584238740,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:132",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pgd_offset_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525601,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621579425,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217938,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct",
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307068,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690230,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:preallocate_vmalloc_pages",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:populate_extra_pmd",
        "arch/x86/mm/init_64.c:set_pte_vaddr",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738371,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:_lookup_address_cpa",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597908798,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621788351,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_p4d",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579810727,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings",
        "arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605751,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621932656,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113332,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125888,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:walk_to_pmd",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235811,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240000,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:get_old_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251680,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583256576,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270736,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298080,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_small_pages_range_noflush",
        "mm/vmalloc.c:__vunmap_range_noflush",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480516,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583543333,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset",
        "mm/hugetlb.c:huge_pte_alloc",
        "mm/hugetlb.c:huge_pmd_unshare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597924735,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583682864,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583844978,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583890341,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mm_alloc_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450853,
      "name": "pgd_offset_pgd",
      "external": false,
      "loc": "include/linux/pgtable.h:136",
      "file": "fs/userfaultfd.c",
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
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
pgd_t * pgd_offset_pgd(pgd_t * pgd, long unsigned int address)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
pgd_t * pgd_offset_pgd(pgd_t * pgd, long unsigned int address)
```
</details>
</li>
</ul>

# Function: <code>pte_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578962542,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594976015,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_pte_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994312,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587349772,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281515,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292566,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309405,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657218,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580664798,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pfn",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:follow_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723710,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730971,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580801239,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580810829,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361222,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580895901,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428385,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:145",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578959065,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595142130,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994295,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278293,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280878,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294240,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310010,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580768620,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580801169,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842232,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849861,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580934075,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937242,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862634,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581056702,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616097,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578961129,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595384800,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996135,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293592,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296142,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309740,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325258,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834156,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580865475,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904446,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912775,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920341,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581002395,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581008987,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077340,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581132765,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579956,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581704545,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:156",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578967943,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973096,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596306047,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291116,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293392,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307688,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879513,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910550,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949142,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959335,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964886,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049963,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051275,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303793,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581179685,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639705,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759665,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:178",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578971278,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975820,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998349,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579310698,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579314070,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330033,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602724356,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964391,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009296,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:_vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050129,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581061132,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581071418,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160907,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581162468,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869064,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581250569,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308637,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395204,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785157,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906128,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998349,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579304464,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578973998,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977997,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001742,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579322183,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579340646,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602895791,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100835,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142916,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:_vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581177818,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189039,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200090,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208492,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304058,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312579,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248026,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393095,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454298,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545866,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581960114,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091235,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:192",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001742,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579316512,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972134,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976573,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000638,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579346487,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579367542,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604693100,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178916,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222736,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:_vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258010,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272015,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283509,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289660,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387722,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394115,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490312,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478711,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539151,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581629389,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041269,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186051,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000638,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579341248,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578979142,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983551,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008062,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579362182,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579382382,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604793118,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995289,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249112,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581296401,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336138,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346519,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357870,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364332,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499386,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581506300,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951278,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530065,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581646345,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744537,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202356,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349475,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579008062,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579356624,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578981542,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985919,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010419,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579366422,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579386686,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818839,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049285,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307720,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355169,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391946,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405831,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417539,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423980,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563898,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570668,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178805,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594969,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658121,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718041,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817581,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582283194,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582448339,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010419,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579360864,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991734,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995407,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018442,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd"
      ]
    },
    {
      "addr": 18446744071579393451,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pte_table",
        "arch/x86/mm/init_64.c:remove_pte_table",
        "arch/x86/mm/init_64.c:remove_pte_table"
      ]
    },
    {
      "addr": 18446744071579427199,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609157032,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231934,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499512,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552751,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590170,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604243,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618883,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627253,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774497,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788527,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197110,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809575,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876762,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936948,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_pages",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037809,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570942,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740339,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:213",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018442,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579394711,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578993222,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997327,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591242790,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd"
      ]
    },
    {
      "addr": 18446744071579383570,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579397696,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pte_table",
        "arch/x86/mm/init_64.c:remove_pte_table",
        "arch/x86/mm/init_64.c:remove_pte_table"
      ]
    },
    {
      "addr": 18446744071579426895,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612227526,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274529,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539679,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597407,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636570,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651537,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665159,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672949,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822641,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835951,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692012,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857191,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581924538,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581979499,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_pages",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582086685,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643262,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811667,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587940845,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591242790,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071591267291,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579001958,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579005903,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591185906,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579384958,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579400950,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579429905,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614368308,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291169,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563007,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ]
    },
    {
      "addr": 18446744071581620044,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_reuse",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ]
    },
    {
      "addr": 18446744071581658138,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672339,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581687217,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699382,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581851857,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866767,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591634779,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892323,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947450,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582007511,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110494,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671275,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840403,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587822376,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185906,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071591209617,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071581562064,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581584800,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579019638,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023855,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592048078,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579446828,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579463288,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579494087,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615299859,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535459,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581827674,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ]
    },
    {
      "addr": 18446744071581887548,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ]
    },
    {
      "addr": 18446744071581926490,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581941751,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961227,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971178,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143206,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582157802,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172380,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ]
    },
    {
      "addr": 18446744071582186996,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252091,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309895,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378828,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426809,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997531,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583173171,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588427395,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592048078,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071592083321,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071581826688,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581850496,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071582170368,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038663,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042444,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593814637,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ]
    },
    {
      "addr": 18446744071579521889,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579539605,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579574447,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579604955,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884391,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582220639,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page"
      ],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ]
    },
    {
      "addr": 18446744071582243307,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ]
    },
    {
      "addr": 18446744071582333274,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582351525,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380527,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394354,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582596166,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613047,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582631022,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_pte",
        "mm/sparse-vmemmap.c:vmemmap_p4d_range"
      ],
      "caller_func": [
        "mm/sparse-vmemmap.c:__populate_section_memmap",
        "mm/sparse-vmemmap.c:__populate_section_memmap",
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ]
    },
    {
      "addr": 18446744071582646722,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743069,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582806120,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582879693,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582941824,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668514,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589828374,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:186",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593814637,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579533232,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071582217872,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071582243616,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071582628384,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068218,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072060,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627537180,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579622128,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579643054,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683077,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718760,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317600,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545157,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_look_around"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582710026,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739179,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ]
    },
    {
      "addr": 18446744071582833866,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852829,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884007,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900622,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583112607,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121909,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583136450,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596456713,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166633,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272576,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583346401,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583428545,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583498635,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584275254,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585097265,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:187",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732544,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068074,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071868,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619283158,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636064,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579657102,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579696933,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579732370,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518758,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582693957,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582924931,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954667,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn"
      ]
    },
    {
      "addr": 18446744071583049245,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069401,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098859,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115752,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583323104,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332181,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583346757,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596998076,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382833,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495871,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583558680,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583649649,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583713639,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584505702,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585326839,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:188",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949024,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579093162,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097292,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621575590,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665856,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579690974,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731461,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767314,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582687662,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867813,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583099112,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126645,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range"
      ]
    },
    {
      "addr": 18446744071583191690,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583231165,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251273,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281143,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298648,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544739,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583568337,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_pte_entry",
        "mm/hugetlb_vmemmap.c:vmemmap_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583582749,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597927404,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622316,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:break_ksm_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683725,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758592,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583844465,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583914383,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584735030,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_category",
        "fs/proc/task_mmu.c:pagemap_hugetlb_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585561543,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:224",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127392,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282402512,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/kernel/mce_power.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/mce_power.c:addr_to_pfn",
        "arch/powerpc/kernel/mce_power.c:addr_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282443320,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/kernel/eeh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282718752,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable.c:maybe_pte_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282724880,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/mm/pgtable_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable_64.c:pmd_page",
        "arch/powerpc/mm/pgtable_64.c:pud_page",
        "arch/powerpc/mm/pgtable_64.c:pgd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282741000,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/mm/book3s64/hash_utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282809408,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/mm/book3s64/hash_64k.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_4K"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/mm/book3s64/hash_hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/mm/book3s64/hash_hugepage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282844416,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/hugetlbpage.c:follow_huge_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283314308,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/kvm/book3s_64_vio_hv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283329820,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/kvm/book3s_hv_rm_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:real_vmalloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283363856,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "arch/powerpc/perf/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/callchain.c:read_user_stack_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286058536,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286076652,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286182688,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286199944,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286209532,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286425272,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286427820,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297817324,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286573168,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286613700,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286652840,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286815856,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287481940,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean",
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287719900,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:617",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271360268,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "arch/riscv/mm/cacheflush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/cacheflush.c:flush_icache_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272713902,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272722176,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272770606,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272776392,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272781886,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272900200,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270896982,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273031768,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273427866,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273559064,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:179",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578981894,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986271,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010771,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579362326,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579382590,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732719,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018133,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276568,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324017,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360794,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581374679,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386387,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392828,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532634,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539404,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781093,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563705,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626857,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686777,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786317,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251930,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417075,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010771,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579356768,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292993,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312115,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700439,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581223002,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267787,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304505,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318210,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329158,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335430,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474433,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481144,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589503939,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581568001,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625829,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724494,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189642,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353847,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578981478,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985855,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010355,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579362246,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579382510,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810286,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009333,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267768,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315217,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351994,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581365879,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377587,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384028,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523946,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530716,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590224501,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555017,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618169,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678089,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777629,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242410,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582407555,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010355,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579356688,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```

```json
{
  "name": "pte_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578982070,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986639,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013571,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579370678,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579391300,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604822996,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070584,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331624,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379171,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415930,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429767,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441438,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448044,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588874,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590186,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590274859,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620065,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686611,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744716,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846626,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319997,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582487059,
      "name": "pte_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:211",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579013571,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579365120,
      "name": "pte_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```
</details>
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
long unsigned int pte_pfn(pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int pte_pfn(pte_t pte)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
long unsigned int pte_pfn(pte_t pte)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
